FLASHDROP WEBSITE

Files:
- index.html: website structure/content
- style.css: black-and-white responsive design
- script.js: platform selector, mobile menu, social profile links and interactions
- assets/: supplied logo and five cropped screenshots from your ZIP
- downloads/: put your Android APK here

IMPORTANT BEFORE PUBLISHING
1. Copy your real Android APK into downloads/ and name it exactly:
   flashdrop-android.apk
2. Open script.js and replace the sample Facebook, TikTok, Instagram and WhatsApp URLs with your own profile links.
3. In index.html, replace [Your full name] and the MY STORY paragraph with your real bio.
4. Replace the YOUR PHOTO placeholder in the developer section with your own portrait. Save it as assets/developer-photo.jpg and change the photo-placeholder block in index.html to:
   <img class="developer-portrait" src="assets/developer-photo.jpg" alt="Your name">
   Add this CSS rule to style.css:
   .developer-portrait{width:100%;height:100%;object-fit:cover}
5. Update version/build information in the download section when you have the final release details.

HOW TO PREVIEW
- Extract the ZIP.
- Open index.html in Chrome, Edge or Firefox.
- For a hosted site, upload the full folder contents to your hosting provider.

The website uses HTML, CSS and vanilla JavaScript only. Google Fonts are loaded online; the rest of the site assets are local.
