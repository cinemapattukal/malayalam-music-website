Malayalam Music Album Page Update

Files to upload to the GitHub repository root (replace existing files):
- index.html (adds Latest Albums section on Home)
- album.html (album listing and album details page)
- admin.html (adds Albums tab to the existing admin panel)

Also update Firestore Rules using firestore.rules.txt. It adds public read/admin-only write access for the albums collection. Keep the UID as your authorized admin UID.

Admin album fields: name, year, imageUrl, totalTracks, director, starring, released. The homepage and album page read these fields from the same Firebase project, malayalam-music-website.

For songs to appear inside an album, the Song record's Album / Movie field must exactly match the album name.
