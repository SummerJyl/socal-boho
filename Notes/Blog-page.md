# Blog Content Planning

## Content Pillars
- Lifestyle & Wellness
- Beauty & Skincare Reviews
- Sustainable Living & Eco-Friendly Tips
- Boho Style & Decor
- Southern California Coastal Vibes

## Post Ideas
- Seasonal skincare routines
- Product reviews & recommendations
- How-to guides (e.g., creating a boho-inspired home)
- Creator tips and social media strategies
- Local spotlights & adventures in SoCal

## Posting Schedule
- Frequency (e.g., weekly, biweekly)
- Preferred publishing days/times

## Goals
- Increase engagement
- Grow Pinterest & Instagram followers
- Collaborate with brands aligned with SoCal Boho values

---

*Optional: Drafts, keywords, and SEO targets can be noted here as you build posts.*

## ==============================
   Layout
============================== ##
main {
  margin: 0 auto;
  max-width: 800px;
  padding: 1rem;
  text-align: center;
}

## ==============================
   Header & Navigation
============================== */
.logo {
  cursor: pointer;
  display: inline-block;
  font-family: 'Playfair Display', serif;
  font-size: 2rem;
  font-weight: 700;
  letter-spacing: 1px;
  margin: 0;
  padding: 0;
  text-transform: uppercase;
}

nav a {
  color: #333;
  display: inline-block;
  margin: 0 1rem;
  padding: 0.5rem 0;
  text-decoration: none;
  transition: color 0.3s ease;
}

nav a:hover,
nav a:focus {
  color: #9c7b5a;
  outline: none;
}

## ==============================
   Blog Posts & Content
============================== */
.blog-posts,
.social-pinterest {
  margin-bottom: 2rem;
}

.blog-post {
  border-bottom: 1px solid #ddd;
  margin-bottom: 2rem;
  padding-bottom: 1rem;
  text-align: left;
}

.blog-post img {
  display: block;
  margin: 0 auto 1rem;
  max-width: 100%;
  height: auto;
}

.read-more {
  background-color: #9c7b5a;
  border-radius: 4px;
  color: white;
  display: inline-block;
  margin-top: 0.5rem;
  padding: 0.5rem 1rem;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.read-more:hover {
  background-color: #755a3c;
}

## ==============================
   Cards / Picks
============================== */
.pick-card {
  background-color: #faf5f0;
  border: 1px solid #ddd;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  margin: 1rem 0;
  padding: 1rem;
  text-align: center;
  transition: box-shadow 0.3s ease;
}

.pick-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

## ==============================
   Brand Logos / Section
============================== */
.brands {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: 2rem 0;
  gap: 1.5rem;
}

.brands img {
  max-height: 60px;
  object-fit: contain;
  transition: opacity 0.3s ease;
}

.brands img:hover {
  opacity: 0.7;
  cursor: pointer;
}

## ==============================
   Pinterest Widget
============================== */
.social-pinterest a[data-pin-do] {
  display: block;
  margin: 0 auto;
}
