# DilliBagCo — Website Design Brief
*Hand this to Claude Code to continue development*

---

## Brand Overview
- **Store name:** DilliBagCo (written as one word, no dot)
- **Product:** Handcrafted bags made in Delhi
- **Price range:** ₹5,000 – ₹10,000
- **Tagline:** "Crafted by Hand. Carried for Life."
- **Target customer:** Urban Indian women, 25–45

## Brand Personality
Vibrant, warm, playful — modern Delhi craft brand. NOT dark luxury. Think bold colour, handmade pride, homegrown energy.

---

## Design System

### Colours
| Name          | Hex       | Usage                        |
|---------------|-----------|------------------------------|
| Cream         | #f7f2e4   | Page background              |
| Tomato Red    | #C93638   | Primary — buttons, accents   |
| Coral         | #FA855A   | Secondary accents            |
| Sunset Yellow | #FED794   | Badges, hero panel           |
| Dark          | #1a1008   | Text, footer background      |
| Muted         | #7a6a58   | Secondary text               |
| Off-white     | #fffdf6   | Card backgrounds             |

### Typography
- **Headings:** Fraunces (serif, weight 700/900) — Google Fonts
- **Body / UI:** DM Sans (sans-serif, weight 400/500/600) — Google Fonts
- **Logo:** Use the actual Logo.jpeg file — do NOT recreate it in text/CSS

### Buttons
- Primary: `background #C93638`, white text, `border-radius 6px`, `padding 11px 24px`
- Outline: transparent bg, `border 1.5px solid #C93638`, red text, same radius

### Badges
- Red badge (Bestseller): `background #C93638`, white text
- Yellow badge (New in / Story): `background #FED794`, `color #7a4a00`

---

## Image Assets (place in project folder)
| File         | Usage                            |
|--------------|----------------------------------|
| Logo.jpeg    | Header + footer logo             |
| Banner.png   | Homepage hero — full width       |
| 8.png        | Product: The Sunshine Stripe Tote|
| 6.png        | Product: The Mughal Garden Tote  |
| 4.png        | Product: The Madras Quilt Shopper|
| 1.jpeg       | Additional product / hero image  |

---

## Pages to Build

### ✅ 01_homepage.html — DONE
Sections built:
1. Announcement bar — red strip, white text
2. Header — logo centred, nav left, icons right
3. Hero — Banner.png full width, cream gradient overlay left side, headline + CTA overlaid on left half
4. Featured Products — 3 product cards in a grid
5. Brand Story — red background, stats grid (50+ artisans, 100% Delhi, 5K+ customers, Zero fast fashion)
6. Footer — 4 columns: logo+social, Shop, Help, Newsletter signup

### 🔲 02_product_page.html — TODO
- Large product image gallery (main image + thumbnails)
- Product title, price in ₹
- Short description
- Size/colour selector if applicable
- "Add to Bag" button (primary red)
- Product details accordion (Materials, Dimensions, Care)
- "You may also like" section (3 related products)

### 🔲 03_collection_page.html — TODO
- Page header with collection name
- Filter bar (by type, price, etc.)
- Product grid (3 columns)
- Pagination or load more

### 🔲 04_about_page.html — TODO
- Brand story hero
- Artisan section
- Values/mission

### 🔲 05_contact_page.html — TODO
- Contact form
- Store info

---

## Shopify Context
- Theme name: DilliBagCo Theme
- Shopify 2.0 (JSON templates)
- The HTML mockups will be converted to Shopify Liquid sections
- Key files in Shopify: sections/, templates/, assets/, layout/theme.liquid
- User edits code via: Shopify Admin → Online Store → Themes → Edit Code

---

## Technical Notes
- All mockups are standalone HTML files (no build tools needed)
- Images referenced by filename (e.g. `src="Banner.png"`) — keep all files in same folder
- Use Google Fonts via @import in `<style>` tag
- No frameworks — plain HTML + CSS only
- Test by opening .html file directly in Chrome

---

## Conversation History
This brief was generated from a design session in Claude.ai where:
- The design direction was confirmed as "vibrant & playful" (not dark luxury)
- Logo file was provided and must be used as-is (not recreated)
- Banner.png was chosen as the hero image
- Product images 8.png, 6.png, 4.png were confirmed as product photos
- Homepage mockup (01_homepage.html) was completed and is included in this folder

