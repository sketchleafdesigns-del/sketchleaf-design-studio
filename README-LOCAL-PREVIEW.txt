SKETCHLEAF — LOCAL PREVIEW
==========================

This build uses YouTube for the commercial videos and lightweight WebP posters on the page.
The YouTube iframe is loaded only after the visitor clicks a video/playlist button.

IMPORTANT:
Do NOT double-click index.html to test the YouTube player. YouTube embeds can fail when the HTML file is opened directly from the file system because there is no HTTP Referer/context. YouTube documents this behavior.

Recommended preview on Windows:
1. Extract this ZIP.
2. Open Command Prompt/PowerShell in the Old_sketchleaf folder.
3. Run:
   python -m http.server 4173
4. Open:
   http://localhost:4173/

Then test:
- Hero layout and animations
- Selected Work -> Load Commercials
- Portfolio cards -> Watch Commercial
- Mobile layout
- Navigation and enquiry form

The live Vercel deployment provides the normal HTTPS webpage context for the YouTube embed.

YouTube playlist:
https://www.youtube.com/playlist?list=PLQBbGG5a1-9Y
