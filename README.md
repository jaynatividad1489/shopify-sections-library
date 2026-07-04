# 🎨 Shopify Sections Library

> A collection of production-ready, reusable Liquid sections for Shopify — built for developers who care about clean code, performance, and merchant experience.

![Shopify](https://img.shields.io/badge/Shopify-Compatible-96BF48?style=flat-square&logo=shopify&logoColor=white)
![Liquid](https://img.shields.io/badge/Liquid-Templating-0090D6?style=flat-square)
![CSS3](https://img.shields.io/badge/CSS3-Responsive-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📦 What's Inside

| Section | Description | File |
|---|---|---|
| 🖼️ **Hero Banner** | Full-width hero with image, overlay, heading, and dual CTA buttons | `sections/hero-banner.liquid` |
| 💬 **Testimonials Slider** | Auto-playing customer review slider with star ratings and dot navigation | `sections/testimonials-slider.liquid` |
| ❓ **FAQ Accordion** | Accessible expandable FAQ with single/multi-open mode | `sections/faq-accordion.liquid` |
| 🛍️ **Featured Products** | Responsive product grid with sale badges, hover image, and quick add | `sections/featured-products.liquid` |

**Shared Assets:**
- `snippets/section-header.liquid` — Reusable heading/subheading snippet
- `assets/sections.css` — Shared styles with CSS custom properties (design tokens)

---

## ✨ Features

- ✅ **100% Liquid** — no external dependencies or third-party apps required
- ✅ **Theme Editor Ready** — every setting is configurable via Shopify's drag-and-drop editor
- ✅ **Mobile-First Responsive** — looks great on all screen sizes
- ✅ **Accessible** — ARIA attributes, keyboard navigation, reduced motion support
- ✅ **Performance Optimized** — lazy loading, efficient CSS, minimal JavaScript
- ✅ **Clean, commented code** — easy to understand, extend, and maintain

---

## 🚀 How to Use

### Option 1 — Copy & Paste (Quick Start)
1. Open your Shopify Theme Editor → **Edit Code**
2. Navigate to the `sections/` folder
3. Click **"Add a new section"**
4. Paste the contents of any `.liquid` file from this repo
5. Save and add the section to your page via the Theme Editor

### Option 2 — Shopify CLI
```bash
# Clone this repo
git clone https://github.com/jaynatividad1489/shopify-sections-library.git

# Copy sections to your theme
cp sections/*.liquid your-theme/sections/
cp snippets/*.liquid your-theme/snippets/
cp assets/sections.css your-theme/assets/
```

### Option 3 — Download ZIP
Click **Code → Download ZIP** at the top of this page, then copy files manually into your theme.

---

## 📁 File Structure

```
shopify-sections-library/
│
├── sections/
│   ├── hero-banner.liquid          # Full-width hero section
│   ├── testimonials-slider.liquid  # Customer review slider
│   ├── faq-accordion.liquid        # FAQ accordion
│   └── featured-products.liquid    # Product grid with quick add
│
├── snippets/
│   └── section-header.liquid       # Reusable section heading snippet
│
├── assets/
│   └── sections.css                # Shared CSS with design tokens
│
└── README.md
```

---

## 🛠️ Customization

All sections are fully customizable via the **Shopify Theme Editor** without touching code:

### Hero Banner Settings
| Setting | Description |
|---|---|
| Background Image | Upload any image as the hero background |
| Overlay Opacity | Control darkness of image overlay (0–90%) |
| Section Height | Set height in pixels (300–900px) |
| Content Alignment | Left, Center, or Right |
| Heading & Colors | Full color control for all text |
| Primary & Secondary Buttons | Label, URL, and color for both CTAs |

### Testimonials Slider Settings
| Setting | Description |
|---|---|
| Autoplay | Enable/disable with custom speed (2–8 seconds) |
| Star Rating | Per-testimonial 1–5 star rating |
| Author Photo | Optional author image or auto-generated avatar |
| Up to 12 blocks | Add as many testimonials as needed |

### FAQ Accordion Settings
| Setting | Description |
|---|---|
| Single Open Mode | Only one item open at a time (toggle) |
| Rich Text Answers | Full rich text support for answers |
| Contact Prompt | Optional "Still have questions?" CTA |
| Up to 20 blocks | Add as many FAQ items as needed |

### Featured Products Settings
| Setting | Description |
|---|---|
| Collection Picker | Select any collection from your store |
| Products to Show | 2–12 products |
| Column Layout | 2, 3, or 4 columns on desktop |
| Hover Image | Show secondary product image on hover |
| Quick Add | One-click add to cart for single-variant products |

---

## 🖥️ Browser Support

| Browser | Support |
|---|---|
| Chrome | ✅ Full |
| Firefox | ✅ Full |
| Safari | ✅ Full |
| Edge | ✅ Full |
| IE 11 | ❌ Not supported |

---

## 📋 Roadmap

- [ ] Image + Text Split Section
- [ ] Announcement Bar
- [ ] Product Tabs Section
- [ ] Newsletter Signup with Klaviyo integration
- [ ] Before/After Image Slider
- [ ] Countdown Timer Section
- [ ] Multi-column Content Section

---

## 👤 Author

**John Venedick Natividad**
Senior Shopify Developer & Implementation Specialist
14+ years building eCommerce experiences for global brands

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/jaynatividad)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat-square&logo=github)](https://github.com/jaynatividad1489)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jaynatividad1489@gmail.com)

---

## 📄 License

MIT License — free to use in personal and commercial projects.
If this helped you, a ⭐ star on the repo is always appreciated!
