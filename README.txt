MEGHA DHANKANI — DIGITAL RESUME
================================

This is a single-scroll digital resume. It has no top navigation tabs.

PREVIEW AND EDIT
1. Keep index.html and the assets folder together.
2. To view the page, double-click index.html and open it in Chrome.
3. To edit the text or image crop, right-click index.html and choose Open with > Notepad.
   (Notepad++ or Visual Studio Code are also suitable if already installed.)
4. Save the file, then refresh the Chrome tab to see your changes.

HOW TO ADJUST IMAGE CROPPING
In index.html, search for:
  .profile{... object-position:50% 25% ...}
This changes the portrait crop. Try 50% 15% to show more of the top, or 50% 40%
to move the visible crop lower. The first percentage moves left/right; the second
moves up/down.

For the four gallery photos, search for the comment 'Adjust the crop of each gallery
image'. Each photo has its own line, for example:
  .gallery .photo-workshop{object-position:50% 40%}
Change the two percentages, save, and refresh Chrome. 50% 50% is centred.
The image files themselves are not changed; only the visible crop on the page changes.

IMPORTANT: Keep the assets folder beside index.html. The photos and videos load from it.

PUBLISH A SHAREABLE LINK
1. Extract the complete ZIP file.
2. Open https://app.netlify.com/drop
3. Drag the extracted folder 'megha_yoga_portfolio' onto the page.
4. Netlify publishes the full folder and gives you a public URL.
5. Share that one URL on WhatsApp. Visitors can view the page and play its videos online.

The contact section already includes the supplied mobile number and email address.
