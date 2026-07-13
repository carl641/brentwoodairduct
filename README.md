# Brentwood Air Duct Cleaning

Marketing website for **Brentwood Air Duct Cleaning** — a locally owned air duct,
dryer vent, and HVAC cleaning company serving Brentwood, TN and the surrounding
Middle Tennessee communities.

## Overview

A fast, responsive, SEO-optimized static website built with plain HTML, CSS, and
vanilla JavaScript — no build step or dependencies required.

## Pages

| Page | File | Purpose |
| --- | --- | --- |
| Home | `index.html` | Hero, services overview, why-choose-us, process, reviews, service area, FAQ, quote form |
| Services | `services.html` | Detailed breakdown of each service offered |
| About | `about.html` | Company story, values, and trust signals |
| Service Area | `service-area.html` | Cities and communities served + map |
| Contact | `contact.html` | Contact details and free-estimate request form |

## Services Featured

- Air Duct Cleaning
- Dryer Vent Cleaning
- HVAC System Cleaning
- Air Quality & Sanitizing
- Residential Duct Cleaning
- Commercial Duct Cleaning

## Project Structure

```
.
├── index.html
├── services.html
├── about.html
├── service-area.html
├── contact.html
├── css/
│   └── styles.css
├── js/
│   └── main.js
├── images/
│   ├── hero.svg
│   └── favicon.svg
├── robots.txt
└── sitemap.xml
```

## Features

- Fully responsive design (mobile, tablet, desktop) with a mobile nav menu
- Local SEO: unique titles/meta descriptions, canonical URLs, `robots.txt`,
  `sitemap.xml`, and `HVACBusiness` JSON-LD structured data
- Accessible, semantic markup with keyboard-friendly FAQ accordion
- Quote / contact forms with client-side success messaging
- Click-to-call phone links and a floating mobile call button
- Embedded Google Maps service-area map

## Running Locally

It's a static site — just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customization Notes

Before going live, replace the following placeholders with real business details:

- **Phone number:** `(615) 857-5923` (used in `tel:` links and content)
- **Email:** `info@brentwoodairduct.com`
- **Address:** Maryland Farms, Brentwood, TN 37027
- **Domain:** `https://www.brentwoodairduct.com/` (canonical/OG tags & sitemap)
- **Social links:** the footer social icons currently point to `#`
- **Form backend:** forms show a client-side success message only; connect them to
  a real handler (e.g. Formspree, Netlify Forms, or your CRM) to receive leads
