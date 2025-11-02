# Priyanka — Driving Instructor Portfolio

## Overview
This is a fast, responsive portfolio website for Priyanka, a professional driving instructor. It showcases services, pricing, testimonials, areas covered, FAQs, and a booking/contact form. The site is built with semantic HTML, accessible components, and lightweight, inline CSS/JS to ensure it loads quickly on any device.

Key features:
- Fully responsive layout from mobile to desktop
- Accessible navigation with mobile menu
- Clear calls to action to book lessons
- Lesson types, pricing packs, and testimonials
- Booking form (client‑side demo) with helpful fields
- Contact details and operating hours
- SEO‑friendly metadata and LocalBusiness schema
- Zero external dependencies for fast loads

## Setup
- No build tools required.
- Files:
  - index.html — Main application (HTML/CSS/JS inline)
  - README.md — Documentation and license

To run locally:
- Option 1: Open index.html directly in your browser.
- Option 2: Serve with a simple static server for best results:
  - Python 3: python -m http.server 8080
  - Node (npx): npx serve .
  - Bun: bunx serve .

Deploy:
- Upload both files to any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
- Ensure index.html is at the project root.

## Usage
- Customize text:
  - Update name, bio, and copy in the hero and sections.
  - Replace placeholders: phone, email, hours, and area names.
- Pricing:
  - Adjust prices/labels in the Pricing section or replace with “Request quote”.
- Contact form:
  - The form currently shows a confirmation alert only (no backend).
  - To make it functional, connect to your preferred service or backend endpoint:
    - Example: change the submit handler in index.html to POST to your API.
- Branding:
  - Replace the inline favicon/data‑URI with your own if desired.
- Accessibility:
  - Keep labels with inputs and retain focus styles.
- Performance:
  - The site uses no external libraries or fonts, ensuring sub‑second first render on typical connections.

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