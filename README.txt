YOUR WEBSITE — QUICK REFERENCE
================================

PREVIEW
  Double-click index.html to open it in your browser.

EDIT THE BASICS
  Open index.html in a text editor, scroll to "QUICK SETTINGS"
  near the top of the <script> section (near the bottom of the
  file) — set her name and your Formspree link there if you want one.

ADD PHOTOS / SONG / MEME
  Put your files in assets/images, assets/audio, assets/video.
  Inside index.html, each dashed placeholder box has an HTML
  comment right next to it with the exact code to paste in.

ADD MORE QUESTIONS
  On page 2 (in index.html), copy one of the blocks marked
  <!-- ===== ... QUESTION ===== --> and paste it below with a
  new id (like q6). Add it to collectAnswers() near the bottom
  of the script if you're using Formspree.

CHANGE COLORS
  Edit the hex values in the :root { ... } block near the top of
  <style>. Two ready-made alternate palettes are commented out
  right below it — just swap the whole block in.

GO LIVE (so she can open it from a link)
  See the chat for full deploy steps (GitHub Pages / Netlify Drop).
  Once you have a link, that's what your QR code will point to.

Full walkthrough is in the chat where this was built.
