MALAYALAM MUSIC WEBSITE

Files:
- index.html: song listing page. Song title / cover / Song Details opens song.html?id=...
- song.html: separate song details page with YouTube embedded player and Google Drive direct-download link.

IMPORTANT SETUP:
1. In BOTH index.html and song.html, edit the `music` array.
2. Keep the same `id` for the same song in both files.
3. Replace the placeholder YouTube URL https://www.youtube.com/watch?v=VIDEO_ID with the real YouTube video URL.
4. Replace the cover URL and song metadata.
5. driveId is the file ID from a Google Drive share URL. The file must be shared so intended users can access it.
6. Use only audio files you own or are authorized to distribute.
7. Upload BOTH index.html and song.html to the same GitHub Pages repository root and commit changes.

YouTube uses the official embedded player and will show video; it cannot be forced into an audio-only player using a normal video URL. The Google Drive download link may open a confirmation page for large files and is subject to Drive limits.
