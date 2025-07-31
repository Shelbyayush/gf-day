# **Girlfriend Day Webpage**

This is a special multi-page webpage created for Girlfriend Day, featuring customizable photos, videos, messages, and audio. It's designed to be a heartfelt and personal gift.

## **Project Structure**

* index.html: The landing page.  
* html/: Contains all subsequent pages (page2.html to page8.html).  
* css/: Contains style.css for all styling.  
* audio/: Store your customizable MP3 audio files here.  
* gif/: Store your customizable GIF files here.  
* img/: Store your customizable image files (background, portraits, moments) here.

## **Customization**

To personalize this webpage, replace the placeholder content with your own:

1. **Images (img/ folder):**  
   * background.jpg: Replace with your desired 1920x1080 image of lilacs, white roses, or both.  
   * pic1.jpg \- pic6.jpg: Replace with your portrait pictures for pages 3, 4, and 5\.  
   * moment1.jpg \- moment4.jpg: Replace with your pictures for page 6\.  
   * Ensure all images are in .jpg or .png format.  
2. **Audio (audio/ folder):**  
   * audio1.mp3 \- audio7.mp3: Replace with your desired audio files for each page.  
   * Ensure all audio files are in .mp3 format.  
3. **GIF (gif/ folder):**  
   * hugging\_characters.gif: Replace with your chosen animated GIF for page 2\.  
4. **Text Content (in HTML files):**  
   * Open each HTML file (index.html, html/page2.html, etc.) in a text editor.  
   * Look for comments like \<\!-- CUSTOMIZABLE TEXT \--\> or \<\!-- REPLACE WITH YOUR MESSAGE \--\>.  
   * Edit the text content within the relevant HTML tags (e.g., \<h1\>, \<p\>, \<span\>).  
5. **Font:**  
   * The current font is 'Dancing Script'. If you want to change it, open css/style.css.  
   * Find the @import url(...) line at the top and the font-family properties.  
   * You can choose another font from [Google Fonts](https://fonts.google.com/) and update the import link and font-family names accordingly.

## **How to Deploy on GitHub Pages**

Follow these steps to make your webpage shareable:

1. **Create a GitHub Repository:**  
   * Go to [GitHub](https://github.com/) and log in.  
   * Click the \+ sign in the top right corner and select New repository.  
   * Give your repository a name (e.g., girlfriend-day-webpage).  
   * Choose Public (so it can be viewed as a webpage).  
   * Do **NOT** initialize with a README.md (we're providing one).  
   * Click Create repository.  
2. **Upload Your Files:**  
   * On your new repository page, click on the uploading an existing file link.  
   * Drag and drop all the files and folders from your girlfriend\_day\_webpage/ directory (including index.html, css/, html/, audio/, gif/, img/, and README.md) into the upload area.  
   * Add a commit message (e.g., "Initial commit: Girlfriend Day Webpage").  
   * Click Commit changes.  
3. **Enable GitHub Pages:**  
   * Once your files are uploaded, go to the Settings tab of your repository.  
   * In the left sidebar, click on Pages.  
   * Under Branch, select main (or master if that's your default branch) from the dropdown and choose / (root) for the folder.  
   * Click Save.  
4. **Access Your Webpage:**  
   * GitHub Pages will now build your site. This might take a few minutes.  
   * Refresh the Pages section in Settings after a short while.  
   * You will see a message like "Your site is published at https://yourusername.github.io/your-repository-name/".  
   * Click on this link to view your live Girlfriend Day webpage\!

## **Enjoy\!**

I hope this webpage brings a smile to your girlfriend's face. Happy Girlfriend Day\!