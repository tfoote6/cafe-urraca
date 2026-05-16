# Cafe Urraca Website

A modern, simple, and dynamic website for Cafe Urraca built with Tailwind CSS, vanilla JavaScript, and your beautiful logo.

## Files Included
- `index.html` — Main / Home page (hero, signatures, testimonials, values)
- `discovery.html` — About / Story page (our nest, values, location)
- `menu.html` — Fully interactive menu with filters, search, cart system
- `assets/logo.jpg` — Your original logo (used on every page header)

## Features
- **Consistent header** on all pages with:
  - Your logo perfectly centered
  - Vertical navigation (MAIN / DISCOVERY / MENU) on desktop left side
  - Mobile hamburger menu with vertical layout
  - "Reserve Table" call-to-action
- **Color palette locked** to your logo: soft cream background, urraca blue (#3A7CA5), gold accent (#C9A227), dark text
- **Modern & dynamic**:
  - Smooth hover animations & micro-interactions
  - Interactive menu with live search + category filters (Coffee, Signature, Pastries, Savory)
  - Fully functional shopping cart with add/remove/quantity + toast notifications
  - Testimonials, newsletter signup, confetti on add-to-cart
  - Easter eggs (type "bird" on menu page for surprise)
- Fully responsive (mobile-first)
- Self-contained (no external dependencies except Tailwind CDN & Font Awesome CDN for icons)

## How to Deploy on Porkbun
1. Log in to your Porkbun account
2. Go to your domain (the one you purchased)
3. Navigate to **Hosting** → **Static Site** (or File Manager)
4. Upload the entire `urraca-cafe` folder contents (or zip it first and upload)
5. Set the **index file** to `index.html`
6. Your site will be live at your domain (e.g. cafeurraca.com or whatever you chose)

**Recommended**: Upload all files to the root of your hosting or a `/cafe` subdirectory.

## Customization Tips
- Replace any `https://picsum.photos/...` image URLs with your own high-quality photos (coffee, interior, food)
- Update address, hours, and social links in the footer of each page
- Change prices or add/remove menu items easily in the `menuItems` array in `menu.html`
- For real orders, connect the cart to a service like Stripe, Square, or a simple form

## Local Testing
Just open `index.html` in any browser. Everything works offline.

---

**Built with curiosity** for Cafe Urraca • San Salvador, El Salvador

If you need any changes (new pages, different colors, more items, booking system, etc.) just let me know!