# Amarence Consults — Website Demonstration

A responsive, single-page website concept for Amarence Consults, based in Port Harcourt, Nigeria. Built as a Lumina Forge client-pitch demonstration.

## Run locally

Open `index.html` in a modern browser. No build step or package installation is required.

## Creative direction

**The Connected Advantage** — an editorial, calm and confident presentation of three connected service areas:

- Corporate services
- Finance and accounting
- Travel assistance

The interface uses an asymmetrical hero, an interactive service explorer, a considered approach narrative and a direct enquiry section. It avoids generic three-column feature-card layouts.

## Design and motion references

This implementation draws on:
- **GPT Taste**: AIDA page narrative, varied composition, strong headline hierarchy, restrained component count and clear action paths. Reference: [GPT Taste skill](https://github.com/Leonxlnx/taste-skill-classics/tree/main/skills/gpt-tasteskill).
- **Lumina Forge Website Animation & Interaction Prompt Library**: staggered hero entrance, transform/opacity section reveals, restrained hover feedback, touch-safe behavior and reduced-motion support.
- **Sandra engineering standards**: semantic HTML, keyboard interaction, responsive layouts, graceful no-JavaScript content visibility, performance-conscious assets and explicit disclosure of demo-only behavior.

No GSAP or other animation dependency was added. CSS transitions and Intersection Observer are sufficient for this site's restrained motion requirements. The service explorer is a keyboard-operable tab interface.

## Important content and launch notes

This is a **demonstration**, not an approved final company website. Public-facing service categories were used as a preliminary content basis and must be confirmed by Amarence before launch. In particular, verify the exact scope and availability of CAC, trademark, SCUML-related, accounting, finance and travel services.

- Do not treat illustrative photography as Amarence premises, staff or client work.
- No testimonials, awards, client logos, statistics or professional credentials have been invented.
- The location is represented at city level only: Port Harcourt, Rivers State, Nigeria.
- No phone number, email address or street address is published because approved contact details have not yet been supplied.
- The enquiry form validates input and displays a local demo confirmation only. It does not send, store or transmit enquiries. Connect an approved inbox/CRM endpoint and add appropriate privacy information before launch.
- Replace stock photography with approved brand photography where available.
- Confirm company naming, brand identity, service descriptions and all legal/compliance wording with the client.

## Technical notes

- Static HTML, CSS and vanilla JavaScript; no package dependencies.
- Responsive navigation with accessible expanded state.
- Service tabs support mouse, touch and arrow-key navigation.
- Form uses native validation and clearly discloses its demo-only status.
- Motion respects `prefers-reduced-motion`; content remains visible when JavaScript or Intersection Observer is unavailable.
- Google Fonts and Unsplash imagery are external assets; a production deployment should consider self-hosting fonts and optimizing approved image assets.
- Metadata and minimal ProfessionalService JSON-LD are included; review structured data and final SEO details against confirmed business information before launch.

## Next client-input checklist

1. Confirm the three service divisions and exact service catalogue.
2. Supply approved logo, brand colors and any brand guidelines.
3. Supply the official phone, WhatsApp, email and business address.
4. Confirm preferred enquiry destination and privacy/data handling requirements.
5. Supply approved staff, office and service imagery, plus any testimonials that can be attributed and published.
