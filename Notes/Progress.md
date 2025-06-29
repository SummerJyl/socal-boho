📝 SoCal Boho Site — Progress Notes
✅ Major Accomplishments:
Pinterest site verification:
✅ Meta tag added to <head> and successfully verified.

Blog Template Created:
✅ Structure built with article, blog post image, text, and “Read More” link.

Pinterest Board Widget Embedded:
✅ Pinterest section added and styled. Adjusted to center-align.

Contact Form Modal:
✅ Modal added and now working on all pages (/index, /about, /blog).
⚠️ Fixed issue where it only worked on /index.

About Me Page:
✅ About section with profile image and bio added.
✅ CSS updated to use flexbox for image + text layout.
✅ Responsive fixes for smaller screens.

Removed "Featured On" Section:
✅ Removed brand logos section to declutter layout.

Instagram/TikTok Embed:
✅ Tested LightWidget (⚠️ HTTPS issue in free version).
✅ Replaced with Elfsight widget — working version.

"Currently Loving" Section:
✅ Horizontal scrollable product cards styled using Flexbox.
✅ Cards centered and text styled.
✅ Swapped placeholder images with personal content.

Font Improvements:
✅ Changed from 'Poppins' to 'Quicksand' to better complement the logo.

Hero Section Background Image:
✅ Added header-bg.jpg as hero background.
✅ Fixed major issue with image not rendering due to incorrect relative path.

🛠️ Common Errors & Fixes
Issue	Fix
Pinterest meta tag not showing	Committed correctly and confirmed in browser View Source
Blog posts left-aligned	Added .blog-post styling and container alignment
Image too large	Applied max-height and width: 100% with object-fit: cover
Contact form only worked on /index	Ensured shared JS and HTML modal code on all pages
Navbar overlapping content	Used Flexbox in header and min-height adjustments
style.css not loading on /about	File path was incorrect → Fixed with correct relative path
Background image not loading	Fixed relative path in CSS: url('../assets/images/header-bg.jpg')
Footer stacking vertically	Used Flexbox to place text and icons side by side

🧠 Lessons / Best Practices
Always verify file paths in relation to the CSS file, not the HTML.

Use F12 > Network tab to check for 404 errors and what’s failing to load.

Centralize reusable elements like nav and modals using includes/JS where possible.

Add commits frequently and write descriptive messages to trace changes.

Use hard refresh (Cmd + Shift + R) to clear GitHub Pages cache.