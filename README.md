# Amro Studio Showcase Website

Static showcase website built with Astro + Tailwind CSS.

## Scope Included

- 5 pages: Home, About, Services, Projects, Contact
- Project gallery section
- Contact form (Formspree endpoint placeholder)
- WhatsApp click-to-chat integration
- Responsive layout for mobile, tablet, and desktop
- Build output ready for Cloudflare Pages deployment

## Run Locally

```sh
npm install
npm run dev
```

Production build:

```sh
npm run build
npm run preview
```

## Form Setup

1. Create a Formspree form (or Web3Forms account).
2. Open `src/pages/contact.astro`.
3. Replace `https://formspree.io/f/your-form-id` with your real endpoint.

## WhatsApp Setup

Update the WhatsApp number in these files:

- `src/components/WhatsAppButton.astro`
- `src/components/Footer.astro`
- `src/pages/contact.astro`

Use international format without `+` or spaces.

## Deploy To Cloudflare Pages

1. Push this project to GitHub.
2. In Cloudflare Pages, create a new project from that repository.
3. Build settings:
   - Build command: `npm run build`
   - Build output directory: `dist`
4. Deploy.

This setup keeps monthly hosting cost near zero on the free tier.
