# Priyanka — Cooking Instructor Portfolio

## Overview
A fast, responsive portfolio website for Priyanka, a professional cooking instructor. It highlights services, class formats, pricing, testimonials, areas served, FAQs, and a booking form. The site is built with semantic HTML, accessible components, and lightweight inline CSS/JS for instant loads on any device.

Key features:
- Fully responsive layout (mobile to desktop)
- Accessible navigation with mobile menu
- Clear calls to action to book classes
- Class formats and popular class themes
- Transparent pricing with an instant cost estimator
- Booking/contact form (client‑side demo)
- Contact details and hours
- SEO‑friendly metadata and JSON‑LD schema
- Zero external dependencies for performance

## Setup
No build tools required.

Files:
- index.html — Main application (HTML/CSS/JS inline)
- README.md — Documentation and license

Run locally:
- Open index.html directly in your browser, or
- Serve with a simple static server:
  - Python 3: python -m http.server 8080
  - Node (npx): npx serve .
  - Bun: bunx serve .

Deploy:
- Upload both files to any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
- Ensure index.html is at the project root.

## Usage
- Customize text:
  - Update name, bio, and copy in the hero and sections.
  - Replace contact details (phone, email), hours, and service areas in the Areas section.
- Pricing:
  - Adjust prices in the Pricing section and the estimator logic in index.html:
    - Private/online base rates
    - Per‑person group rate
    - Ingredient add‑on
    - Travel fee per km and included radius
- Booking form:
  - Currently shows a confirmation alert only (no backend).
  - To make it functional, connect to your preferred service or backend endpoint:
    - Replace the setTimeout in the submit handler with fetch('/api/book', { method: 'POST', body: FormData }) and handle responses.
  - The form autosaves to localStorage so users don’t lose progress.
- Branding:
  - Replace the inline favicon (chef hat SVG) or colors in the :root CSS variables.
- Accessibility:
  - Labels remain associated with inputs; focus styles are provided. Use semantic headings and landmarks.
- Performance:
  - No external fonts or libraries. All assets are inline for sub‑second first paint.

## Improvements in Round 2
This round converts the previous “Driving Instructor” portfolio into a “Cooking Instructor” site and adds several enhancements:
- Content overhaul:
  - Replaced all driving‑specific content with cooking‑specific copy: class formats, menus, dietary needs, and kitchen prep guidance.
- New sections and details:
  - Popular classes with themes (Indian basics, baking, meal prep, regional focus).
  - Areas served updated for in‑person and online worldwide.
- Pricing + estimator:
  - Added an interactive estimator to preview costs (format, participants, travel, ingredients, extended session).
- Accessibility and UX:
  - Clearer focus styles, semantic headings, higher contrast, and descriptive labels.
  - Mobile navigation improvements with ARIA attributes and close‑on‑link behavior.
- SEO updates:
  - JSON‑LD schema updated to Person (Cooking Instructor) with OfferCatalog for classes.
  - Improved meta description and favicon aligned with the new theme.
- Performance:
  - Maintained zero dependencies and inline assets for fast loads.
  - Kept layout lightweight and responsive.

## License
MIT License

Copyright (c) 2025 Priyanka

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.