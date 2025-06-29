# 📓 SoCal Boho Site — Progress Notes

## ✅ Accomplishments

### 🔧 Core Features Implemented
- **Pinterest Site Verification**
  - Added `<meta name="p:domain_verify">` to `<head>` of `index.html`
  - Verified successfully on Pinterest

- **Blog Page Template**
  - Added `<article>` with image, title, meta text, excerpt, and "Read More"
  - Integrated Pinterest Board widget, styled for center alignment

- **Contact Modal**
  - Working across `/index`, `/about`, and `/blog`
  - Fixed broken modal on non-home pages by including required JS & modal HTML
  - Triggered with `id="contactBtn"` link

- **About Me Section**
  - Profile image + text displayed side-by-side with Flexbox
  - Responsive layout tweaks for smaller screens
  - Replaced placeholder image with personal photo

- **Social Embeds**
  - Tested LightWidget (failed HTTPS)
  - Replaced with **Elfsight** Instagram widget → Success

- **Currently Loving Section**
  - Scrollable horizontal card layout (`.featured-picks`, `.pick-card`)
  - Swapped out dummy images for personal picks
  - Centered `.scroll-picks` and improved spacing

- **Typography & Aesthetic**
  - Updated font to `'Quicksand'` for harmony with logo
  - Reduced nav and header spacing to allow full content + footer visibility without scroll

- Added `header-bg.jpg` as hero background
  - Fixed major rendering issue due to incorrect file path

## 🐞 Common Errors & Resolutions

| Issue | Resolution |
|-------|------------|
| Meta tag not visible | Verified via browser View Source after Git push |
| Pinterest widget misaligned | Wrapped in container + centered with Flexbox |
| Blog post image too large | Added `max-height: 400px; object-fit: cover;` |
| Contact form not appearing on all pages | Copied modal HTML + JS script to each relevant file |
| Navbar overlapping text | Adjusted header layout and spacing |
| `style.css` not loading on subpages | Fixed relative file paths |
| Background image not rendering | Corrected path relative to `style.css` file |
| Footer stacking | Styled with Flexbox to be horizontal on desktop |
| Font too modern | Switched from `'Poppins'` to `'Quicksand'` for softer style |

## 💡 Tips & Lessons

- Always confirm file paths relative to **the CSS file**, not the HTML
- Use **DevTools > Network** tab to catch `404` errors
- Modular HTML (nav, modals) could be reused via JS includes
- Git commits with clear messages = easier debugging
- Use **hard refresh (Cmd+Shift+R)** on GitHub Pages updates

---

**Next Up:**
- Swap out remaining placeholder images with real content
- Consider breaking out reusable elements (header, footer) into includes
- Fine-tune spacing & image sizing for mobile/tablet views
