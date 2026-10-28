# SPACO Corporation

> **Material movement, made easier to explore.**

A polished, responsive website concept for **Spaco Corporation**, a material-handling equipment supplier in MIDC Kupwad, Sangli, Maharashtra. The experience is designed to help visitors discover equipment categories, understand potential industrial applications, and start a business enquiry.

<p>
  <img src="https://img.shields.io/badge/React-19-20232A?logo=react&logoColor=61DAFB" alt="React 19" />
  <img src="https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white" alt="Vite 8" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4" />
  <img src="https://img.shields.io/badge/TypeScript-5.7-3178C6?logo=typescript&logoColor=white" alt="TypeScript 5.7" />
</p>

## Overview

This project presents an editorial, industrial visual direction for Spaco Corporation:

- Forest-green, lime, and warm paper palette
- Strong condensed typography for an equipment-led identity
- Responsive layout for desktop, tablet, and mobile
- Product discovery with search and category filtering
- Hash-based navigation with shareable page URLs
- Quote and contact enquiry forms
- Clear concept and verification notices wherever company information or imagery still needs confirmation

> **Important:** This is a demonstration website concept prepared by PS Services. Product availability, technical specifications, imagery, company details, and submitted-enquiry handling require confirmation before publication or production use.

## Experience map

| Route | Purpose |
| --- | --- |
| `#home` | Hero, product discovery, applications, and enquiry call-to-action |
| `#about` | Company concept and positioning |
| `#products` | Searchable and filterable equipment catalogue |
| `#product/<name>` | Detail view for an equipment category |
| `#industries` | Potential industries and material-handling applications |
| `#gallery` | Project and image placeholders awaiting verified assets |
| `#quote` | Full quotation request form |
| `#contact` | Contact details, directions, and enquiry form |
| `#faq` | Frequently asked questions |
| `#privacy` | Draft privacy policy and publication checklist |

## Equipment categories

The current concept includes these preliminary categories:

1. Conveyor Systems
2. Bag Stackers
3. Truck Loading Systems
4. Bale Breakers
5. Bag-Handling Systems
6. Portable Belt Conveyors
7. Platform Trolleys & Hand Carts

These are presented as discovery categories, not as verified product claims.

## Tech stack

- **React 19** for the interface and component structure
- **TypeScript 5.7** for type-safe page and product models
- **Vite 8** for development and production builds
- **Tailwind CSS 4** through the Vite plugin
- **Inter** and **Barlow Condensed** via Google Fonts
- **Oxfmt** for formatting

## Getting started

### Prerequisites

- Node.js compatible with the project toolchain
- pnpm

### Install dependencies

```bash
pnpm install
```

### Start the development server

```bash
pnpm dev
```

Vite will print the local URL in the terminal. The app supports hot reload while you edit files.

### Create a production build

```bash
pnpm build
```

### Preview the production build

```bash
pnpm preview
```

### Format the project

```bash
pnpm format
```

## Project structure

```text
.
├── public/
│   ├── favicon.svg
│   ├── robots.txt
│   └── sitemap.xml
├── src/
│   ├── App.tsx          # Pages, product data, navigation, and forms
│   ├── index.css        # Theme tokens, responsive styles, and layout
│   ├── main.tsx         # React entrypoint
│   └── vite-env.d.ts    # Vite type declarations
├── index.html           # Document metadata and application shell
├── package.json         # Scripts and dependencies
├── tsconfig.json        # TypeScript configuration
└── vite.config.ts       # Vite and Tailwind configuration
```

## Content and production checklist

Before publishing this concept as an official company website:

- [ ] Confirm the company name, address, phone number, and map location
- [ ] Replace illustrative Unsplash imagery with approved Spaco photography
- [ ] Verify every product category, description, and technical specification
- [ ] Add a real enquiry endpoint or CRM integration
- [ ] Define acknowledgement, validation, and error states for form submissions
- [ ] Replace draft privacy content with an approved privacy policy
- [ ] Review SEO, social preview images, and sitemap entries
- [ ] Confirm accessibility content, including final image alt text

## Design principles

The interface intentionally balances industrial credibility with approachable discovery:

- **High contrast:** dark green surfaces and lime actions make primary paths obvious.
- **Structured rhythm:** generous sections and strong typographic hierarchy keep technical content scannable.
- **Honest content states:** concept notices distinguish illustrative content from verified company information.
- **Progressive discovery:** visitors can move from a category to a detail page, then into a quotation enquiry.
- **Responsive first:** navigation, grids, forms, and content blocks adapt for smaller screens.

## License and attribution

This repository contains a private website concept for Spaco Corporation. Do not reuse company-specific copy, branding, contact details, or imagery without permission.

The current visual concept uses remote images from [Unsplash](https://unsplash.com/). Replace them with approved, locally managed assets before production deployment.
