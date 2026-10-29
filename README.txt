See Through — booklet viewer for the web

1. Put it on GitHub Pages (free)
   a. Sign in at https://github.com and click + (top right) → New repository.
      Name it e.g. see-through, set it to Public, click Create repository.
   b. On the new repository page click "uploading an existing file".
      Drag in everything INSIDE this folder: index.html, support.js,
      See-Through-Alex-Westfall.pdf, README.txt and the "pages" folder.
      (If "pages" won't drag in, use Add file → Upload files and drop the folder there.)
      Click Commit changes.
   c. Go to Settings → Pages. Under "Build and deployment" choose
      Source: Deploy from a branch, Branch: main, folder: / (root). Click Save.
   d. After a minute or two the page shows your link:
      https://YOURNAME.github.io/see-through/

2. Add it to Cargo
   In the Cargo editor, open the page, switch to Code view (the </> button) and paste:

   <iframe src="https://YOURNAME.github.io/see-through/" style="width:100%;height:85vh;border:0;" allow="fullscreen" allowfullscreen loading="lazy" title="Alex Westfall: See Through"></iframe>

   Replace YOURNAME (and see-through, if you named the repository differently). Adjust 85vh (height) to taste.

3. Updating later
   Upload the changed files the same way (Add file → Upload files); files with the same name are replaced.
   Changes can take a few minutes to show. Keep the folder structure as-is.

4. The "Download PDF" link downloads See-Through-Alex-Westfall.pdf from this folder — keep it next to index.html.
