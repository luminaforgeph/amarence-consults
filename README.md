# Amarence Consults — Website Demonstration

A responsive, single-page brand experience for Amarence Consults, based in Port Harcourt, Nigeria. Built by Lumina Forge as a client-pitch demonstration.

## Run locally

Open `index.html` in a modern browser. No build step or package installation is required.

## Creative direction

**Confidence, without complexity.** The experience positions Amarence as a sophisticated international professional-services brand for both businesses and individuals. Its design language combines monumental architectural imagery with a warm editorial palette, a typographic wordmark, generous negative space and carefully composed asymmetry.

The experience moves through an architectural opening statement, the Amarence perspective, an interactive expertise index for corporate, financial and travel assistance, a considered client-approach narrative, and a clear invitation to begin an enquiry.

## Visual system

- Warm ivory: `#F3F0E8`
- Deep evergreen: `#17251F`
- Mineral paper: `#E8E4DA`
- Muted champagne: `#B7A57D`
- Editorial display: Cormorant Garamond
- Interface and body: DM Sans
- Sharp, architectural edges; no decorative rounded-card system.

## Motion and interaction

Motion follows the Lumina Forge Website Animation & Interaction Prompt Library: short staggered hero entrance using opacity and transform; restrained architectural image reveal; Intersection Observer section reveals using opacity and translateY; keyboard-operable expertise tabs with a small content transition; simple mobile navigation and immediate interaction feedback. No animation framework, cursor gimmicks, heavy parallax, WebGL or blocking preloader. `prefers-reduced-motion` disables nonessential movement, and touch layouts do not depend on hover.

## Content and launch notes

This is a **demonstration**, not an approved final company website. Service categories and examples are provisional and must be confirmed by Amarence before launch, particularly the exact scope of CAC, trademark, SCUML-related, accounting, finance and travel services.

- Photography is illustrative stock imagery; it does not represent Amarence premises, staff, clients or completed work.
- No testimonials, awards, client logos, statistics, staff profiles, qualifications or professional credentials have been invented.
- The location is represented at city level only: Port Harcourt, Rivers State, Nigeria.
- No phone number, email address or street address is published because approved contact details have not been supplied.
- The enquiry form validates input and displays a local demonstration confirmation only. It does not send, store or transmit enquiries. Connect an approved inbox/CRM endpoint and add appropriate privacy information before launch.
- Confirm the company's exact name, service catalogue, brand identity, legal/compliance wording and all public-facing claims with the client.
- Replace stock photography with approved brand imagery where available.

## Technical notes

- Static HTML, CSS and vanilla JavaScript; no package dependencies.
- Mobile-first layout with compact mobile navigation and deliberately re-composed mobile sections.
- Semantic landmarks, skip link, visible focus states, meaningful image alt text and keyboard-operable expertise tabs.
- Native form validation and explicit demo-only disclosure.
- Motion content remains visible if JavaScript or Intersection Observer is unavailable.
- Google Fonts and Unsplash imagery are external assets. Consider self-hosting fonts and optimizing approved image assets for production.
- Metadata and minimal ProfessionalService JSON-LD are included; review structured data and final SEO details against confirmed business information before launch.

## Client inputs required before launch

1. Confirm the service divisions and exact service catalogue.
2. Supply approved logo/brand guidelines if the typographic wordmark should be replaced or adjusted.
3. Supply official phone, WhatsApp, email and business address.
4. Confirm enquiry destination, privacy wording and data-handling requirements.
5. Supply approved office, team and service imagery, plus any testimonials that can be attributed and published.
