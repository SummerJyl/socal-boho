# socal-boho
# SoCal Boho Website

Welcome to the SoCal Boho lifestyle blog website project! This repository contains the source code, assets, and styles for a cozy, coastal-inspired blog highlighting curated content, creator tips, and Southern California vibes.

---

## Recent Updates & Changes (2025-06-28)

### 1. Social Icons & Logos
- Created and integrated official SVG and PNG social media icons for:
  - Amazon
  - LTK (shopltk)
  - Pinterest
  - Instagram
  - TikTok
- Moved all icons into `/assets/icons/` for better organization.
- Resolved broken image paths by standardizing folder locations and fixing `src` attributes.
- Adjusted icon sizes for visual balance:
  - Amazon and LTK icons set to width ~120px.
  - Pinterest icon resized to width ~50px.
- Added proper `alt` attributes and `aria-label`s for accessibility.

### 2. Favicon Setup
- Added favicon link tag in `<head>` of `/index.html` referencing `/assets/icons/favicon.png`.
- Recommended favicon sizes: 16x16, 32x32, 48x48.
- Discussed converting logos to `.ico` format for best browser support.
- Suggested using online tools like [favicon.io](https://favicon.io/) or [RealFaviconGenerator](https://realfavicongenerator.net/) for favicon generation.

### 3. Typography & Styling
- Standardized fonts using Google Fonts:
  - Primary font: `'Poppins', sans-serif` for body text.
  - Accent font: `'Playfair Display', serif` for logo and section headings.
- Added CSS for logo and social section headings with respective font families and colors matching site palette.
- Adjusted header layout:
  - Used `display: flex` with `justify-content: space-between` and `align-items: center` for header.
  - Replaced text logo with image logo in upper-left.
  - Fixed navigation alignment and spacing.

### 4. Hero Section Improvements
- Styled hero section with:
  - Background image with `background-position: center`, `no-repeat` and `cover`.
  - White text overlay (`color: #fff`) for readability.
  - Added padding and centered text alignment.
- Updated hero copy to:  
  `"Curated content, creator tips, and coastal vibes straight from Southern California."`
- Included a CTA button linking to blog pag
