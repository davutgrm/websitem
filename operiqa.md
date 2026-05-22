# Operiqa — Project Brief for Claude Code

## Company Identity

- **Name:** Operiqa
- **Tagline:** Développez votre entreprise grâce à l'automatisation intelligente.
- **Type:** AI automation agency
- **Location:** France
- **Languages:** French (primary) + English

---

## Target Clients

Operiqa serves small and medium-sized businesses (SMBs/PMEs) in four specific sectors:

1. **E-commerce** — order management, cart abandonment flows, automated product descriptions
2. **Real estate (Immobilier)** — lead qualification, automated visit scheduling, client follow-up
3. **Furniture stores (Mobilier)** — instant quotes, stock management, delivery tracking
4. **Restaurants** — online reservations, QR menu app, review management, online order handling

---

## Services Offered

### 1. AI Chatbot & Customer Service Automation
- 24/7 automated customer support
- FAQ handling, ticket routing
- Reduces support workload by up to 80%

### 2. Content Creation with AI
- Blog articles, social media posts, product descriptions
- Automated visual and video content production
- Content generated in the brand's voice

### 3. Business Process Automation
- Tools: n8n, Make (Integromat), Zapier
- Workflow design and integration
- Real-time data syncing between tools

### 4. Visual & Video Automation by Sector
- **E-commerce:** automated product visuals and promotional videos
- **Real estate:** automated property photo/video generation and tours
- **Furniture:** automated 3D/visual renders and catalog videos

### 5. QR App for Restaurants
- Digital QR menu application
- Order management via QR code
- Customer-facing mobile experience

### 6. Custom AI Agent Development
- Bespoke AI assistants built for specific business needs
- Full integration + ongoing maintenance included

---

## Design System

- **Theme:** Dark (deep black background: `#050505`)
- **Accent color:** Blue `#2563eb`
- **Font:** Manrope (weights 400, 600, 700, 800)
- **UI style:** Minimalist dark tech — slate borders (`#1e293b`), muted text (`#94a3b8`), card backgrounds (`#0f172a`)
- **Framework:** Tailwind CSS (CDN)
- **Border radius:** 8px (rounded-lg)
- **Buttons:** Uppercase labels, `font-size: 11-12px`, `letter-spacing: 0.08em`

### Reference color tokens (Tailwind config already defined):
```
background: #050505
surface-variant: #0F172A
primary-container: #2563eb
on-surface-variant: #94a3b8 (muted text)
outline-variant: #1e293b (card borders)
```

---

## Site Structure (Recommended Sections)

1. **Navigation** — Logo + links (Services, Secteurs, À propos, Contact) + CTA button
2. **Hero** — Tagline, subheading, two CTAs (Prendre rendez-vous / Découvrir nos services)
3. **Trusted by** — Placeholder client logos (grayscale, low opacity)
4. **Sectors** — 4 cards: E-commerce, Immobilier, Mobilier, Restauration
5. **Services** — 6 service cards with icons
6. **About** — Short brand philosophy paragraph
7. **Testimonials** — 2–3 client quotes
8. **Final CTA** — Full-width call to action
9. **Footer** — Logo, nav links, legal

---

## Contact Information

| Channel | Details |
|---------|---------|
| Email | davut@operiqa.com |
| Phone | +33 07 58 86 77 14 |
| WhatsApp | +33 07 58 86 77 14 |

---

## Copy Guidelines

- **Tone:** Professional, precise, trust-building. Not salesy.
- **Brand voice:** "La précision mécanique au service de l'humain." — technology that elevates, not replaces.
- **Hero headline style:** Bold claim + blue accent on key phrase (see existing design)
- **CTA text:** "Prendre rendez-vous" (primary) / "Découvrir nos services" (secondary)

---

## Existing HTML Reference

The client already has a working HTML prototype built with Tailwind CSS dark theme. Claude Code should:
- Maintain the same visual identity (dark, blue accent, Manrope)
- Expand the services section to include all 6 services listed above
- Add the 4-sector section with relevant icons and copy
- Integrate contact details into a contact form/section
- Make the site bilingual: French + English (language toggle or separate pages)
- Ensure mobile responsiveness

---

## Notes for Claude Code

- Do NOT change the brand name, color, or font.
- The QR restaurant app is a standalone service — give it its own card with a distinct icon.
- Visual/video automation services should be grouped under one section but broken out per sector.
- All CTAs should link to a contact form or `mailto:davut@operiqa.com` as fallback.
- WhatsApp button can use `https://wa.me/33758867714`.ss