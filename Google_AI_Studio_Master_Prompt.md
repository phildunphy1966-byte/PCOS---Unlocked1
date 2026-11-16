# Google AI Studio Master Prompt — PCOS Unlocked

You are a senior product designer, health-education content designer and experienced frontend engineer. Build a complete, responsive, multi-page educational website called **PCOS Unlocked** with the tagline **“Understand your body. Question the myths. Find your way forward.”**

Use the uploaded `PCOS_Unlocked_Complete_Dossier.md`, `json/project.json`, and `json/content_seed.json` as the source of truth for project requirements. Implement all sitemap routes listed in the dossier. Do not stop after building a homepage or a visual prototype.

## Required application
Build a functioning website with:
- all sitemap routes and meaningful page content;
- consistent header, footer and breadcrumbs;
- responsive desktop and mobile navigation;
- working search;
- optional age selection and editable learning pathway;
- shared body-literacy and PCOS content;
- female learning pathway;
- male ally pathway;
- interactive labelled diagrams;
- menstrual-cycle explainer;
- insulin/metabolism explainer;
- myth-versus-fact interaction;
- educational quiz with answer explanations;
- FAQs;
- Find Support section;
- appointment preparation page with print-friendly layout;
- About, Sources, Accessibility and Privacy pages;
- helpful 404 page.

## Homepage
Use:
Headline: “Your body deserves clear answers.”
Subheading: “Explore PCOS, hormones and reproductive health through clear explanations, interactive visuals and myth-busting guides.”
Primary actions: “Explore PCOS” and “Choose your learning route”.
Keep the first screen simple and instantly understandable. Show clear entry cards for Know Your Body, Understand PCOS, Female learning path, Male ally path and Find Support.

## UX and navigation
- Implement every route in the dossier sitemap.
- Every card, nav item and CTA must lead somewhere real.
- Browser back/forward and direct URL refresh must work.
- The mobile menu must open, close and close after route selection.
- Search must navigate to actual page results and show a useful empty state.
- Users can skip age/pathway onboarding, change their choice and access shared pages.
- Age adaptation changes language depth/examples, not essential access.
- Use breadcrumbs on nested pages and related-topic links to avoid dead ends.

## Interaction
Implement functional accordions, tabs, diagram hotspots, cycle stepper, myth/fact reveal, quiz and print action. All controls must work with keyboard and touch. Provide visible focus states and accessible labels. Interactive diagrams must have equivalent text descriptions.

## Visual design
Follow the dossier's palette and editorial visual direction: calm, clear, warm, contemporary and inclusive. Avoid childish cartoons, excessive pink coding, medical stock-photo clichés and unnecessary animation. Use the supplied SVG assets if present. If not present, create original simple SVG diagrams locally. Do not hotlink random images or copy the reference site's artwork.

## Medical and safety requirements
This is an educational resource, not a diagnostic tool. Display this disclaimer: “PCOS Unlocked is an educational resource. It does not provide a diagnosis or replace advice from a qualified healthcare professional.”
Do not diagnose, create a symptom checker, provide medication doses, promise a cure, stigmatise weight, imply PCOS is caused by lifestyle or menstrual products, or make deterministic fertility claims. Explain adult and adolescent diagnosis pathways separately as described in the dossier. Medical pages must show source links and honest review status. Do not claim clinician review unless it occurred.

## Pathways
The female pathway focuses on experiences, menstrual/reproductive health, diagnosis, care and wellbeing.
The male pathway is an ally pathway: understanding PCOS, challenging myths, listening, respecting privacy and supporting someone. Never imply males have PCOS.
Shared foundational pages remain accessible to everyone.

## Data and privacy
The supplied CSV datasets do not contain gender or direct awareness questions. Do not make gender comparisons, prevalence claims, diagnoses or causal claims from them. Do not collect sensitive health information. No accounts, symptom tracker, cycle tracker, diagnosis feature or health chatbot. At most, store optional age/pathway preference locally; do not store health answers.

## Technical expectations
Prefer React + TypeScript and a routing library if available. Use reusable components and data-driven route definitions. Use semantic HTML, responsive CSS and local assets. Ensure every route has real content and no lorem ipsum.

## Completion protocol
Before reporting completion:
1. List every implemented route.
2. Test each route, including direct URL loading and refresh.
3. Test header/footer, breadcrumbs, mobile menu, search and all interactive components.
4. Test browser back/forward.
5. Test keyboard-only navigation and screen-reader labels.
6. Test mobile and desktop layouts.
7. Check contrast and reduced-motion behaviour.
8. Check sources, disclaimers and medical claims.
9. Report any limitations honestly.

Build the complete application now. Prioritise clarity, accuracy, accessibility and smooth navigation over visual effects.
