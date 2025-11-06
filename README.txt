Ekya Schools — Single Page Landing (GitHub Pages ready)
-----------------------------------------------------

Files included:
 - index.html  --> Main landing page (references external images and favicon)
 - style.css   --> Styling for the page
 - README.txt  --> This file

Notes & Instructions:
1. The site uses the Ekya Schools logo hosted on Wikimedia Commons:
   https://upload.wikimedia.org/wikipedia/commons/9/9a/Ekya_Schools_logo.png
   This file is licensed CC BY-SA — attribution is required if you reuse/modify it. 
   If you'd prefer to host the logo locally, download the image and replace the <img> src
   in index.html with 'images/ekya-logo.png' and update the favicon link similarly.

2. Hero & section images use Unsplash-hosted images via URL. These will load when the site
   is hosted on the web. If you want all images offline, download and place them into an
   images/ folder and update the src/background-image urls in index.html/style.css.

3. To host on GitHub Pages:
   - Create a new repository (e.g., ekya-landing).
   - Upload the files in this ZIP to the repository root.
   - Go to Settings -> Pages -> Source -> Select 'main' branch and root (/) -> Save.
   - Visit https://<your-username>.github.io/<repo-name>/ after a minute to view.

4. Replace testimonial names/content or logo if you have official assets. The ad code
   placeholder is left as an HTML comment: <!-- Ad code here -->

Attribution for logo (Wikimedia):
 - "Ekya Schools logo.png" — Wikimedia Commons
 - License: CC BY-SA 4.0 — https://creativecommons.org/licenses/by-sa/4.0/
 - Source: https://commons.wikimedia.org/wiki/File:Ekya_Schools_logo.png

If you want, I can also:
 - Replace external image links with local images bundled in the ZIP (need image files).
 - Produce a version with inline-critical CSS for faster ad performance.
 - Create a short README with exact Git commands to push from your local machine.