# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

People in Durham Region (Whitby, Oshawa, Ajax, Brooklin) who need a family doctor. Most are on their phones (about two thirds of visits), often searching "family doctor Whitby accepting patients". Ages range from new parents to older adults. Some prefer to be seen in Hindi or Urdu. Many arrive from the Whitby Clinic website.

What they are trying to work out: is this doctor real, is he taking patients, would I be comfortable with him, and how do I sign up.

## Product Purpose

doctorsyed.ca is Dr. Nihaad Syed's personal site. Its job is to get people onto his patient list at The Whitby Clinic (200 Brock Street North, Whitby, Ontario).

Success means more registrations. The main action is the clinic's new patient waiting list form. Calling 905-668-3378 ext. 3 is the second option, because reception struggles with call volume.

The site is also the start of his personal brand. The same visual system has to work on business cards and any future print or digital material.

## Positioning

Things a neighbouring doctor could not truthfully copy, all confirmed by Dr. Syed:

- Trained in the UK (MBChB Sheffield, MRCGP, DCH, DRCOG; family medicine training in London) and certified in Canada (CCFP).
- Consultations in English, Hindi and Urdu.
- Covers the Wednesday evening walk-in urgent care shift (5 to 8 pm) at the clinic.
- Practises in a building with everything under one roof: X-ray, ultrasound, mammography (OBSP), LifeLabs, pharmacy, dietitian, physiotherapy, massage, orthotics.

## Operating Context

- Single-page static site (HTML/CSS), hosted on Vercel, deployed automatically from GitHub `nihaads/doctorsyed-website`.
- Registration happens on the clinic's form (whitbyclinic.ca/waiting-list), which Dr. Syed cannot change.
- GA4 tracks register clicks and phone clicks.
- Print: business cards from Jukebox (20pt Soft Touch planned). The brand must print well in CMYK on coated stock. The May 2026 run printed too dark because the file was RGB on uncoated paper.

## Capabilities and Constraints

- CPSO advertising rules: no testimonials, no superlatives, no outcome promises, no commercial endorsements, credentials must be accurate.
- Never hyperlink the CPSO public register. Mention licensure as plain text only.
- No em dashes in visible copy.
- No mention of virtual appointments.
- MRCGP reads as an exam passed, not current membership.
- Use Canadian wording ("certified family physician", not "board certified").
- Keep the existing SEO basics: title tag, H1 wording, schema, FAQ, sitemap, GA4 events.

## Brand Commitments

- **Feel (his words):** warm and personal, bespoke, classic but modern.
- **Name:** Dr. Nihaad Syed. Credentials: MBChB, CCFP, MRCGP, DCH, DRCOG.
- **Headshot:** keep the existing one. No new photos.
- **Copy:** the current site copy is in his voice. Refine it, don't replace it.
- **Monogram:** he likes the Ns monogram and wants it developed into a proper logo that feels unique to him. Use it as a signature in a few contained places, never as background pattern or repeated ornament.
- **Retiring:** the cream, navy and amber palette, Cormorant Garamond with Outfit, and the italic amber "Syed". He liked these at first but now sees them everywhere as stock AI design.
- **Past feedback (July 2026 redesign, rejected):** dislikes numbered section labels, drop caps, credentials stacked vertically, photo below text on mobile, and frame details that spill outside the photo. Likes small doses of subtle motion and the nav that shrinks on scroll. Wants changes in small stages he can stop.

## Evidence on Hand

- Headshot: `headshot.webp`, `headshot.jpg`.
- Bio, services, office hours and 8 FAQs in `index.html`.
- One quote that he co-wrote and adopts as his own statement.
- No testimonials, reviews, patient photos or outcome statistics. Never make these up.

## Product Principles

1. Lead with the doctor, not the building. People choose a person.
2. Plain and honest beats impressive. Nothing that would fail a CPSO review.
3. Make registering obvious from every screen, especially on a phone.
4. Personal without self-promotion. The brand should read as a signature, not a billboard.
5. One system for screen and print, from day one.

## Accessibility & Inclusion

- Meet WCAG AA contrast. The current amber-on-cream text fails (2.4:1).
- Design mobile first. Keep text comfortably large for older patients.
- Respect reduced-motion settings.
