# PCOS UNLOCKED
## Complete Website Dossier
**Tagline:** Understand your body. Question the myths. Find your way forward.

**Document purpose:** This dossier is the central product, research, content, UX and implementation brief for building PCOS Unlocked as a complete, responsive, multi-page educational website in Google AI Studio.

---

# 1. Project overview

## 1.1 Project concept
PCOS Unlocked is an inclusive digital learning platform that helps people understand PCOS, reproductive health, menstrual health, hormones, metabolism, diagnosis, management and supportive communication. It uses plain-language explanations, illustrated diagrams, interactive learning, myth-busting and clear signposting to reliable health information.

## 1.2 Core design question
How might a digital learning experience help young people in India understand PCOS accurately, question misinformation and find appropriate next steps without shame, fear or unnecessary complexity?

## 1.3 Purpose
- Make reliable PCOS information easier to understand.
- Build foundational body literacy.
- Reduce stigma and misinformation.
- Help visitors recognise when professional advice may be useful.
- Help friends, partners and family members become informed supporters.
- Present medical information in a calm, non-judgemental and accessible way.

## 1.4 Primary audience
Young women aged 18–25 in India, including:
- people diagnosed with PCOS;
- people who notice symptoms but have not received a diagnosis;
- people who have heard of PCOS but do not understand it;
- people who want to understand their bodies and reproductive health.

## 1.5 Secondary audiences
- Under-18 visitors seeking age-appropriate foundational learning.
- Adults aged 26–30, 31–35 and above 35.
- Men and boys as friends, partners, siblings, family members and allies.
- Parents/carers, educators and peers.

**Important:** The male pathway is an ally-learning pathway. It explains PCOS and how to support someone. It must not suggest that males have PCOS or present a male PCOS diagnosis journey.

## 1.6 Age groups
- Under 18
- 18–21
- 22–25
- 26–30
- 31–35
- Above 35

Age selection is optional. Age changes language, examples and depth—not access to essential information. Visitors can skip onboarding, switch pathways and explore all shared content.

---

# 2. Brand and positioning

## 2.1 Recommended name
**PCOS Unlocked**

## 2.2 Tagline
**Understand your body. Question the myths. Find your way forward.**

## 2.3 Alternative names
- Beyond PCOS
- PCOS, Explained
- The PCOS Project
- Decode PCOS
- PCOS Compass
- Know PCOS

## 2.4 Brand personality
- Clear, reassuring and informed.
- Contemporary and engaging, but not childish.
- Respectful, inclusive and non-judgemental.
- Scientific without sounding like a medical textbook.
- Encouraging without making unrealistic promises.

## 2.5 Brand promise
A visitor should leave each page understanding one useful thing more clearly and knowing where to go next.

---

# 3. Research and dataset audit

## 3.1 Supplied datasets

### Dataset A — `pcos_dataset.csv`
- 1,000 rows × 6 columns.
- Fields: Age, BMI, Menstrual_Irregularity, Testosterone_Level(ng/dL), Antral_Follicle_Count, PCOS_Diagnosis.
- No missing cells in the inspected export.
- This is a structured clinical-style dataset. Its provenance, collection method, population, diagnostic definition and representativeness are not established by the file itself.

### Dataset B — `Cleaned-Data.csv`
- 173 rows × 36 columns.
- Fields include age bands, weight, height, marital status, PCOS, family history, menstrual irregularity, hormonal imbalance, hyperandrogenism, hirsutism, mental health, conception difficulty, insulin resistance, diabetes, cardiovascular disease, diet frequency, vegetarian status, exercise, sleep, stress, smoking, perceived exercise benefit and PCOS medication.
- No missing cells in the inspected export.
- Some health fields contain compound or ambiguous responses. Medication responses include free text and inconsistent wording. Do not treat all entries as verified diagnoses or standard treatment categories.

## 3.2 What the datasets do not establish
- Neither dataset contains gender or direct awareness/knowledge questions.
- They cannot support male-versus-female awareness comparisons.
- They cannot be treated as representative of the Indian population without provenance and sampling evidence.
- They cannot establish causation.
- They must not be used to diagnose an individual.

## 3.3 Responsible use
The CSVs may inform cautious exploratory descriptions of the supplied samples after a documented cleaning and validation process. Any chart must show the sample size, variable definition, denominator and handling of ambiguous responses.

Required note for any future chart:
> These findings describe the supplied dataset only; they are not population estimates and do not establish causation.

Do not infer gender from symptoms, marital status or other variables. Do not infer a diagnosis from a symptom or lab value. Do not imply that weight, diet, exercise, stress or trauma caused PCOS. Do not publish individual-level records.

## 3.4 Primary research
The project also includes separate male and female Google Forms. The female form has an initial general section and branches according to whether the respondent has heard of PCOS or has limited awareness. The female sample previously reported was 49 respondents. The actual form exports must be analysed separately before using numerical findings or making gender comparisons.

---

# 4. Research context and reference sources

## 4.1 Medical and evidence sources
1. WHO — Polycystic ovary syndrome fact sheet: https://www.who.int/news-room/fact-sheets/detail/polycystic-ovary-syndrome
2. 2023 International Evidence-based Guideline for the Assessment and Management of PCOS: https://pmc.ncbi.nlm.nih.gov/articles/10477934/
3. Indian multicentre prevalence study (2024): https://pmc.ncbi.nlm.nih.gov/articles/PMC11581580/
4. Batra et al. systematic review/meta-analysis (2022): https://pmc.ncbi.nlm.nih.gov/articles/PMC9826643/
5. Menstrual cup systematic review (2019): https://doi.org/10.1016/S2468-2667(19)30111-2

## 4.2 India-specific awareness studies
- Chennai young-adult awareness study: https://www.ijrcog.org/index.php/ijrcog/article/view/15381
- Telangana medical students KAP study: https://www.ijcmph.com/index.php/ijcmph/article/view/15094

These are specific study samples, not national estimates. Verify sample size, study design and publication metadata before quoting numbers.

## 4.3 Design reference
Know Your Body Lessons: https://www.knowyourbodylessons.org/

Use this as inspiration for age-appropriate interactive health education, clear topic navigation and accessible learning. Do not copy its text, illustrations, page layouts or brand assets.

---

# 5. Medical content principles

## 5.1 What is PCOS?
Describe PCOS as a common, complex hormonal and metabolic condition with varied presentations. Some people experience irregular ovulation or periods, androgen-related features or polycystic ovarian morphology. Not everyone experiences every feature. The name can be misleading: ovarian appearance alone does not define the condition.

## 5.2 Diagnosis
Explain that diagnosis is made by a qualified clinician after assessment and exclusion of other possible causes.

For adults, current international guidance generally uses two of three features:
1. Ovulatory dysfunction.
2. Clinical or biochemical hyperandrogenism.
3. Polycystic ovarian morphology, with AMH as an adult alternative in guideline contexts.

If irregular cycles and hyperandrogenism are both present, ultrasound or AMH may not be needed.

For adolescents, both ovulatory dysfunction and hyperandrogenism are required; ultrasound and AMH are not recommended for adolescent diagnosis.

The website must not provide a self-diagnosis checklist or diagnostic score.

## 5.3 Lifestyle and management
- Lifestyle does not simply cause or cure PCOS.
- No single diet or exercise approach is best for everyone.
- Advice should be individualised, weight-inclusive and non-stigmatising.
- Medication decisions belong to qualified clinicians.
- Avoid cure promises and deterministic statements about fertility.

## 5.4 Menstrual products
There is no established evidence that pads, tampons or menstrual cups cause PCOS.

## 5.5 Terminology
PCOS remains the familiar public and search term. If discussing emerging terminology such as PMOS, explain that it is an evolving terminology discussion, cite the exact source and date, and do not silently replace PCOS throughout the interface.

## 5.6 Mandatory disclaimer
> PCOS Unlocked is an educational resource. It does not provide a diagnosis or replace advice from a qualified healthcare professional.

Every medical page must show source links and a last-reviewed date. Do not claim clinician review until it has actually occurred.

---

# 6. Key website features

1. Clear, simple landing page.
2. Optional age selection with six age bands.
3. Female learning pathway.
4. Male ally pathway.
5. Shared foundational content accessible to everyone.
6. Know Your Body learning library.
7. Understand PCOS section.
8. Illustrated anatomy and hormone diagrams.
9. Interactive menstrual-cycle explainer.
10. Insulin and metabolism explainer.
11. Myth-versus-fact interaction.
12. Low-pressure educational quiz.
13. FAQs.
14. Find Support section.
15. Appointment preparation page with print option.
16. Search and topic discovery.
17. Related-topic recommendations.
18. Sources and further reading.
19. About, accessibility and privacy pages.
20. Responsive and keyboard-accessible interface.

Do not add login, paid features, symptom trackers, cycle trackers, diagnostic tools, a medical chatbot or sensitive health-data collection.

---

# 7. Card sorting

## 7.1 Proposed cards
- What is PCOS?
- PCOS and the body
- Reproductive anatomy
- The menstrual cycle
- Hormones and the endocrine system
- Insulin and metabolism
- Symptoms and experiences
- Diagnosis: what clinicians assess
- Treatment and management options
- Food, movement, sleep and stress
- Mental wellbeing and body image
- Fertility and pregnancy: facts and myths
- Myths versus facts
- Supporting someone with PCOS
- Menstrual health and respectful communication
- When to seek medical advice
- Preparing for an appointment
- FAQs and knowledge check
- Sources and further reading

## 7.2 Proposed groups
1. Know Your Body
2. Understand PCOS
3. Symptoms, Diagnosis & Care
4. Everyday Wellbeing
5. Myths, Questions & Quizzes
6. Support Someone
7. Find Help & Reliable Sources

## 7.3 Validation
Conduct open card sorting with 5–8 participants from different age groups and genders, then closed sorting using the proposed groups. Ask participants to explain confusing labels. Revise the IA based on observed patterns.

---

# 8. Information architecture

```text
PCOS UNLOCKED
├── Home
├── Start / Choose your learning route (optional)
│   ├── Choose age range (optional)
│   └── Choose pathway
│       ├── Female learning path
│       └── Male ally path
├── Know Your Body (shared)
│   ├── Reproductive anatomy
│   ├── Menstrual cycle
│   ├── Hormones & endocrine system
│   └── Insulin & metabolism
├── Understand PCOS (shared)
│   ├── What is PCOS?
│   ├── Common features and experiences
│   ├── Diagnosis
│   ├── Health associations
│   └── Treatment and management
├── Female learning path
│   ├── Symptoms and experiences
│   ├── Menstrual and reproductive health
│   ├── Diagnosis and care
│   ├── Everyday wellbeing
│   └── Mental health and body image
├── Male ally path
│   ├── PCOS explained
│   ├── Myths and misconceptions
│   ├── What someone may experience
│   ├── Supportive communication
│   └── How to be an ally
├── Learn & Explore
│   ├── Myths vs facts
│   ├── Interactive explainers
│   ├── Knowledge checks
│   └── FAQs
├── Find Support
│   ├── When to seek medical advice
│   ├── Prepare for an appointment
│   ├── Talk to someone
│   └── Reliable resources
└── About
    ├── About this project
    ├── Medical sources & review dates
    ├── Accessibility
    └── Privacy
```

Shared content must remain accessible from both pathways. Age bands adapt content depth and examples but do not create six separate websites.

---

# 9. Sitemap and routes

| Page | Route |
|---|---|
| Home | `/` |
| Choose your route | `/start` |
| Know Your Body hub | `/know-your-body` |
| Reproductive anatomy | `/know-your-body/anatomy` |
| Menstrual cycle | `/know-your-body/menstrual-cycle` |
| Hormones | `/know-your-body/hormones` |
| Insulin & metabolism | `/know-your-body/metabolism` |
| Understand PCOS | `/pcos` |
| PCOS features | `/pcos/features` |
| Diagnosis | `/pcos/diagnosis` |
| Health associations | `/pcos/health` |
| Management | `/pcos/management` |
| Female pathway | `/pathways/women` |
| Female symptoms & experiences | `/pathways/women/experiences` |
| Female wellbeing | `/pathways/women/wellbeing` |
| Male ally pathway | `/pathways/allies` |
| Supporting someone | `/pathways/allies/support` |
| Learn & Explore | `/explore` |
| Myths & facts | `/explore/myths` |
| Knowledge check | `/explore/quiz` |
| FAQs | `/explore/faqs` |
| Find Support | `/support` |
| When to seek help | `/support/when-to-seek-help` |
| Appointment preparation | `/support/appointment` |
| Reliable resources | `/support/resources` |
| About | `/about` |
| Sources | `/about/sources` |
| Accessibility | `/about/accessibility` |
| Privacy | `/about/privacy` |

All routes must load directly, survive refresh and support browser back/forward. Unknown routes show a helpful 404 page with links to Home, Explore and Support.

---

# 10. Task flows

## Flow A — Understand PCOS
Home → Start Exploring → optional age selection → choose pathway or skip → Understand PCOS → What is PCOS? → explore diagram → common features → diagnosis overview → related topics → sources.

## Flow B — Explore symptoms
Home → Female pathway → Symptoms & experiences → choose topic → read explanation → when to consult a clinician → appointment preparation → return to pathway.

## Flow C — Support someone
Home → Male ally pathway → PCOS explained → myths and misconceptions → everyday impact → supportive communication → practical ways to help → share reliable resources.

## Flow D — Check a claim
Home → Learn & Explore → Myths & Facts → select statement → choose True / False / Not sure → reveal explanation → source → related topic.

## Flow E — Prepare for an appointment
Any page → Find Support → Prepare for an appointment → review discussion prompts → optionally print → learn what a clinician may ask → sources.

## Flow F — Return to a topic
Global navigation/search → select topic → breadcrumb/back link → related topic → home or support.

---

# 11. User flows

## First-time visitor
Landing page explains purpose in plain language. Visitor may choose an age range and pathway, or skip both. Shared content is immediately available. A “Change learning route” control remains accessible.

## Female pathway visitor
Female pathway provides routes into menstrual health, PCOS features, diagnosis, management and wellbeing. Do not assume diagnosis, sexual activity, fertility goals or a particular body type.

## Male ally visitor
The pathway begins with a clear statement that it is for understanding PCOS and supporting someone. It covers the condition, misconceptions, emotional impact and respectful support. It does not present males as patients.

## Under-18 visitor
Use age-appropriate language and foundational body literacy. Encourage questions to a trusted adult or qualified health professional. Do not collect personal information.

## Returning visitor
Global navigation, search, related links and breadcrumbs allow direct access. Optional age/pathway preference may be stored locally, with a clear reset option. Never store health answers.

## Accessibility user
All navigation works by keyboard. Focus states are visible. Interactive diagrams have equivalent text descriptions. Motion can be reduced. Content does not depend on colour alone.

---

# 12. Navigation and interaction design

## Header
- Brand: PCOS Unlocked
- Links: Know Your Body, Understand PCOS, Learn & Explore, Find Support, About
- Search control
- Choose route control
- Mobile menu with accessible open/close behaviour

## Footer
- About
- Medical sources
- Accessibility
- Privacy
- Find Support
- Educational disclaimer

## Navigation rules
- Header and footer on every page.
- Breadcrumbs on nested pages.
- Browser back/forward must work.
- Every page has a clear next step and route back.
- Pathway switcher remains globally available.
- Search results open the relevant route.
- No dead ends.

## Interactions
- Optional age selector.
- Female and male pathway cards.
- Topic cards.
- Keyboard-operable accordions.
- Accessible tabs.
- Diagram hotspots with text alternatives.
- Menstrual-cycle stepper with previous/next and direct phase selection.
- Myth/fact reveal.
- Educational quiz with explanations and restart.
- Search with empty state and Escape-to-close.
- Print-friendly appointment page.
- Optional scroll-to-top control.

## Persistence and privacy
Store only optional age/pathway preference locally if needed. Do not store symptoms, cycle dates, diagnosis status, quiz health answers or other sensitive health data. The site must work if local storage is unavailable.

---

# 13. Page-by-page content blueprint

## Home
**Headline:** Your body deserves clear answers.

**Subheading:** Explore PCOS, hormones and reproductive health through clear explanations, interactive visuals and myth-busting guides.

Primary actions: Explore PCOS; Choose your learning route.

Secondary actions: Know Your Body; Support someone.

Show entry cards for Know Your Body, Understand PCOS, Female learning path, Male ally path and Find Support. Keep the first screen uncluttered.

## Start / Choose your route
Explain that selection is optional. Offer age bands and choices: Female learning path, Male ally path, Explore everything. Users may change route at any time.

## Know Your Body
Explain that understanding anatomy, cycles and hormones makes health information easier to interpret. Link to anatomy, menstrual cycle, hormones and metabolism.

## Reproductive anatomy
Label ovaries, fallopian tubes, uterus, cervix and vagina. State that bodies vary and the diagram is simplified and not to scale. Provide an accessible text description.

## Menstrual cycle
Explain menstrual, follicular, ovulatory and luteal phases as a learning model. Cycle length and timing vary; ovulation does not always occur. Do not present a 28-day cycle as universal.

## Hormones
Explain hormones as chemical messengers. Introduce GnRH, FSH, LH, oestrogen, progesterone, androgens and insulin at an appropriate level. Avoid implying one hormone alone explains PCOS.

## Insulin and metabolism
Explain insulin's role in helping cells use glucose. Insulin resistance can be associated with PCOS for some people, but is not universal and cannot be identified from appearance. Do not suggest weight loss is a cure.

## Understand PCOS
Explain the condition as complex and varied. Not everyone has every feature. Ovarian appearance alone does not define PCOS.

## Features and experiences
Possible features include irregular or absent periods, difficulty predicting ovulation, acne, excess facial/body hair, scalp hair thinning and metabolic features in some people. Symptoms overlap with other conditions; do not turn the page into a diagnosis checklist.

## Diagnosis
Explain adult and adolescent criteria separately, using the clinical principles in Section 5. Encourage clinician assessment and exclusion of other causes.

## Health associations
Explain possible metabolic, sleep-related, psychological and reproductive associations without deterministic language. Individual risk varies.

## Management
Explain that care is individualised and may include cycle regulation, symptom management, metabolic risk management, fertility support when desired, psychological support and lifestyle support. Medication decisions belong to clinicians.

## Female pathway
Focus on lived experiences, menstrual/reproductive health, diagnosis, care conversations, body image and mental wellbeing. Do not assume all users menstruate, want pregnancy or are sexually active.

## Male ally pathway
Explain PCOS, correct myths, discuss stigma and uncertainty, and show how to listen, ask what support is wanted, respect privacy, share reliable information and avoid unsolicited advice.

## Myths and facts
Include:
- “PCOS is only an ovarian problem.” — False/incomplete.
- “Everyone with PCOS has ovarian cysts.” — False.
- “Only people with larger bodies have PCOS.” — False.
- “PCOS means someone cannot become pregnant.” — False.
- “Lifestyle alone cures PCOS.” — False.
- “Pads, tampons or menstrual cups cause PCOS.” — No established evidence supports this.
- “A person can diagnose PCOS from symptoms online.” — False.

## Knowledge check
Use 5–8 educational questions. Explain the answer after each response. Do not score health risk or diagnose.

## Find Support
Explain when professional advice may be useful, including persistent irregular/absent periods, distressing symptoms, new or rapidly worsening symptoms, fertility concerns if relevant, or metabolic/mental health concerns. Avoid alarmist language.

## Appointment preparation
Offer prompts:
- What changes have I noticed, and when did they begin?
- How have my cycles changed, if relevant?
- Which symptoms affect daily life?
- What tests or other causes might need consideration?
- What are the benefits, risks and alternatives of proposed treatments?
- What follow-up is recommended?

## FAQs
Include questions about PCOS meaning, diagnosis, cysts, periods, fertility, weight, lifestyle, treatment, emotional wellbeing, ally support and reliable help.

## About, Sources, Accessibility and Privacy
Explain project purpose and limitations; list sources and review dates; provide accessibility statement; explain that no sensitive health data is collected and clarify optional local preference storage.

---

# 14. Visual design system

## Creative direction
Contemporary editorial health education: calm, clear, warm and scientifically grounded. Avoid hospital stock-photo clichés, pink-only gender coding, childish cartoons, dense textbook layouts and excessive decorative effects.

## Suggested palette
- Deep plum: `#39243F`
- Soft lilac: `#EAE3F0`
- Warm coral: `#E98978`
- Sage: `#A9BBA5`
- Cream: `#FAF7F2`
- Ink: `#242126`
- White: `#FFFFFF`

Test contrast for every text/background pairing.

## Typography
Use a legible sans-serif such as Inter, Atkinson Hyperlegible or system sans for body text. Use a restrained display face for headings. Keep body text readable and line length comfortable.

## Layout
- Responsive desktop grid and single-column mobile layout.
- Generous whitespace.
- Consistent spacing and clear heading hierarchy.
- Topic cards with short descriptions.
- Diagrams as explanatory anchors, not decoration.
- Disclaimers visible but unobtrusive.

## Illustration style
Clean, simplified vector diagrams with clear labels and accessible text alternatives. Included SVGs are educational schematics, not diagnostic or anatomical reference drawings.

## External imagery
Use external assets only after verifying the licence for the exact item. Record creator, URL, licence and attribution. Do not copy images from the reference website or hotlink random images. If rights are uncertain, use the supplied SVGs or original vector artwork.

Suggested asset sources to check:
- https://openverse.org/
- https://commons.wikimedia.org/
- https://unsplash.com/license
- https://www.pexels.com/license/
- https://undraw.co/license

---

# 15. Accessibility requirements

- Semantic HTML landmarks.
- Skip-to-content link.
- Logical heading hierarchy.
- Keyboard-accessible navigation and controls.
- Visible focus indicators.
- Appropriate ARIA roles and labels.
- Text alternatives for every diagram.
- Captions/transcripts for any video/audio.
- Sufficient colour contrast.
- Do not use colour alone to communicate meaning.
- Respect `prefers-reduced-motion`.
- No autoplay audio/video.
- Mobile touch targets must be comfortably usable.
- No horizontal scrolling at common mobile widths.

---

# 16. Technical implementation requirements for Google AI Studio

Build a real multi-page application, not a static homepage mock-up.

Preferred implementation:
- React with TypeScript, if supported.
- A routing library or equivalent robust route handling.
- Reusable components.
- Local SVG assets.
- Responsive CSS.
- Data-driven navigation and content where practical.

Required reusable components:
- SiteHeader
- MobileNav
- SiteFooter
- Breadcrumbs
- TopicCard
- PathwayCard
- Accordion
- Tabs
- DiagramHotspot
- MythFactCard
- QuizQuestion
- SourceList
- Disclaimer
- NotFound

All listed routes must exist and have meaningful content. All navigation items and cards must have working destinations. Direct route loading and refresh must work. Search must be functional. All controls must work by keyboard and touch.

Do not add authentication, subscriptions, symptom tracking, cycle tracking, diagnostic tools, medical chatbot or collection of sensitive health data.

---

# 17. Quality assurance and launch checklist

## Functionality
- [ ] Every sitemap route exists.
- [ ] Direct URL loading and refresh work.
- [ ] Browser back/forward works.
- [ ] Header/footer links work on every page.
- [ ] Mobile menu opens, closes and closes after navigation.
- [ ] Search works and handles no results.
- [ ] Age selection can be skipped, changed and reset.
- [ ] Pathway choice can be skipped and changed.
- [ ] Shared content is accessible from both pathways.
- [ ] Cards, tabs, accordions, hotspots, steppers and quizzes work.
- [ ] Appointment page prints clearly.
- [ ] 404 page has recovery links.

## Content
- [ ] No lorem ipsum or empty pages.
- [ ] No diagnostic quiz or symptom checker.
- [ ] No unsupported causal claims.
- [ ] No claim that everyone with PCOS has ovarian cysts.
- [ ] Adult and adolescent diagnosis guidance are distinguished.
- [ ] Male pathway is ally-focused.
- [ ] Medical sources are linked.
- [ ] Clinical review status is honest.

## Accessibility
- [ ] Keyboard-only navigation works.
- [ ] Focus indicators visible.
- [ ] Skip link works.
- [ ] Heading structure is logical.
- [ ] Controls have labels.
- [ ] Diagrams have text alternatives.
- [ ] Contrast tested.
- [ ] Reduced motion respected.
- [ ] Mobile touch targets are usable.

## Privacy and safety
- [ ] No sensitive health data collected.
- [ ] No login required.
- [ ] No health answers saved.
- [ ] Only optional age/pathway preference stored locally, if at all.
- [ ] Educational disclaimer visible.
- [ ] Medical pages reviewed by a qualified professional before public launch.

---

# 18. Final delivery expectation

The final Google AI Studio result must be a coherent, working, responsive website with every route implemented. It must not be considered complete merely because the landing page looks finished.

Before calling the build complete, the AI Studio agent must:
1. List all implemented routes.
2. Test all navigation and interactive controls.
3. Test mobile and desktop layouts.
4. Test keyboard-only use.
5. Test direct route loading and browser back/forward.
6. Check source links and disclaimers.
7. Identify any remaining limitations honestly.

**The dossier and included JSON files are the specification. The actual application must still be generated and tested in Google AI Studio.**
