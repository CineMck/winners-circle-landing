# Prompt: Build the "Elevate Real Estate" Promo Page

> Paste this prompt to Claude (or any capable coding assistant) in a session that has access to `index.html`. Adjust the bracketed details before sending.

---

## Task

Create a new file `elevate-real-estate.html` in the project root. It's a single-page promo landing for a free Zoom mastermind call targeted at real estate professionals, designed to convert attendees into Elevate-tier members ($495/mo).

## Brand & visual baseline

- **Match the existing `index.html` design system** — same fonts (Inter, weights 300–900), same dark background + gold accent palette (`--bg`, `--gold`, `--gold-dim`, `--gold-lt`, `--text`), same easing variable, same button styles, same nav.
- **But make it feel distinct** as a promo page: add a real-estate-specific accent (e.g., a secondary accent color or subtle texture), a clear "limited spots" urgency bar at the top, and a tighter, more conversion-focused layout (less storytelling, more direct CTAs).
- Keep the same header nav and footer for brand cohesion. Update nav CTA to "Reserve My Spot."

## Offer details (fill in)

- **Event name:** Elevate Real Estate — Free Zoom Mastermind
- **Format:** 1 free live Zoom mastermind call hosted by John Wentworth
- **Audience:** Real estate agents, brokers, and team leaders who want to scale to 7-figure businesses
- **Date / time:** [FILL IN — e.g., Wednesday, June 18 · 12:00pm ET]
- **Duration:** [e.g., 60 minutes + Q&A]
- **Spots available:** [e.g., 25 seats]
- **Price:** Free to attend
- **Post-event offer:** Optional invite to apply for The Winners Circle **Elevate** tier ($495/mo, limited to 10 members)
- **Booking / signup URL:** [PASTE FORM OR CALENDAR LINK]

## Conversion goals

1. **Primary CTA:** Reserve a spot on the free Zoom mastermind (must appear above the fold, sticky on mobile, and repeated 3–4× down the page).
2. **Secondary CTA:** Learn more about Elevate membership (links to `index.html#pricing`).

## Required sections (in order)

1. **Urgency bar** (top, full width): "Only [N] seats left for [DATE]" with a small countdown if practical.
2. **Hero**: Headline focused on what real estate pros will *get* (not what the event is). Subhead: 1–2 sentences. Primary CTA button + small "no cost · no contracts" reassurance below.
3. **Social proof strip**: $1B+ in real estate sales · 500+ members · #1 Independent Brokerage in Michigan.
4. **What you'll learn / take away** (3–5 bullet cards): be specific to real estate — lead gen for agents, listing presentation conversion, scaling a team, recruiting agents, building a referral engine. Use icons consistent with the existing site.
5. **Meet your host** (John Wentworth): condensed version of the index.html "Meet Your Mentor" section. Use existing `john-wentworth.jpg`. Lean into his real estate track record.
6. **Agenda preview**: 3–4 numbered items so attendees know what to expect on the call.
7. **Why now / scarcity**: one-line on limited seats + recording-not-guaranteed framing.
8. **Testimonials**: pull 1–2 video Vimeo embeds already used on `index.html` (real estate-relevant ones if obvious).
9. **Registration form / CTA block**: the conversion moment. Include name + email + brokerage + "what's the #1 thing you want to solve?" field. Big button. Reinforce free + spot limit.
10. **FAQ** (4–6 questions): "Is this really free?", "Will it be recorded?", "Who is this for?", "Will you pitch me?", "What if I can't make the live time?"
11. **Footer**: match `index.html` footer exactly.

## Technical requirements

- Single self-contained HTML file (no external CSS/JS beyond what `index.html` already loads — fonts + Vimeo).
- Mobile-first responsive. Test at 375px, 768px, 1280px breakpoints.
- Sticky mobile CTA bar with the registration button.
- All `YOUR_APP_URL_HERE` placeholders left intact for the user to swap (same pattern as `index.html`).
- SEO: meta title "The Winners Circle — Elevate Real Estate Free Mastermind", meta description mentioning the date and the free offer, canonical link.
- OG + Twitter card meta tags for sharing.
- Accessible: semantic headings, alt text on imagery, form labels, 4.5:1 contrast minimum, focus states on all interactive elements.

## Copy tone

- Direct, confident, real-estate-specific. No "transform your life" fluff.
- Speak to specific RE pain points: stalled pipelines, recruiting struggles, scaling past solo production, falling listing-to-close conversion.
- John's voice: blunt, transparent, zero BS — match the existing "Meet John" copy on `index.html`.

## Deliverables

1. `elevate-real-estate.html` — the new page.
2. A short summary of what you built and any assumptions made.
3. A note on what placeholders still need real values before going live.

## Out of scope (don't do)

- Don't modify `index.html`.
- Don't add a build step, framework, or package dependencies.
- Don't invent stats or testimonials — pull only from what's already in `index.html`.
