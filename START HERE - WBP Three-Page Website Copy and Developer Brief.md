# WE BECAME THE PROOF — Website Handoff
**Three-page responsive website for mobile, tablet, laptop, and desktop | Page copy, layout, sources, and asset directions | November 3, 2026**

## Read this first — developer instructions
Build exactly **three pages**: (1) Home, (2) The 1967 Championship Legacy, (3) Amir Is Still Unhoused / The Morrill Acts. This is an independent **We Became the Proof (WBP)** website. It is **not** a Thoughts 2 Lyfe storefront. Use the WBP logo and WBP visual identity, not T2L purple/teal/gold.

**Visual priority:** WBP identity → mission and connection → three-part model → two education stories. Make the home page inviting and concise. Put the substantive historical education on the two dedicated pages. This document provides the website text, rather than asking the developer to conduct research. All original images referenced below are in the same Drive folder.

**Brand:** Use `WBP_Official_Transparent_Logo.png` or `01_WBP_Brand_Logo.png`. The intended palette is WBP red/deep red, black, white. Exact WBP HEX codes have not been independently confirmed; extract the actual logo's colors into named CSS variables and do **not** substitute the separate T2L colors `#6B2FA8`, `#12AFC4`, `#C9980B`. Use bold, legible heading typography, strong contrast, and accessible body text. Do not generate portraits or change authentic faces/uniforms in historical photos.

**Responsive design is a core requirement, not a mobile-only brief:** Build intentionally for **mobile phones (320–767 px), tablets (768–1023 px), laptops (1024–1439 px), and desktop/large monitors (1440 px and wider)**. These are testing ranges, not mandatory CSS breakpoints; choose fluid layouts and appropriate breakpoints. Give all four formats equal design attention. Wide layouts should use their available space purposefully, with balanced typography, image scale and multi-column cards; tablets should have deliberate layouts rather than merely stretched phone views. The information, accessibility, image quality and interactions must be consistent across devices. Do not hide meaningful content on smaller screens. Test portrait and landscape orientations, no horizontal overflow, readable text, touch targets, navigation, and keyboard use. Deliver screenshots of the home and two education pages at phone, tablet, laptop and large-desktop widths before signoff.

**Navigation:** Home (`/`), 1967 Legacy (`/1967`), Amir & the Morrill Acts (`/amir`). Use navigation appropriate to each screen size (full horizontal navigation on wide screens and an accessible compact menu on narrow screens), a footer with a small WBP/Thoughts 2 Lyfe relationship note, alt text on images, and an obvious back-to-home link. No payments, login, web shop, or speculative impact metrics.

---

# PAGE 1 — HOME
**Route:** `/`

**Layout order:** Header/logo → hero → mission/vision → three simple program cards → why connection matters → two story tiles → closing line/footer. Suggested hero art: `We Became the Proof Triptych.png`, `WBP The Need Banner Preview.png`, or `WBP The Yard Banner Preview.png`. Use the imagery only where readable at each screen size; provide a strong widescreen hero composition as well as a deliberate narrow-screen crop or stack. Do not squeeze text-heavy banners into a small hero.

### Hero
**Eyebrow:** COMMUNITY · IDENTITY · OPPORTUNITY

**H1:** WE BECAME THE PROOF

**Subheading:** Honoring Stories. Creating Opportunities. Strengthening Communities.

**Text:** We Became the Proof is a community-centered initiative that honors lived experience, creates meaningful connections, and opens opportunities for people and communities to thrive.

**Links:** `Our Mission` → mission section; `Explore the 1967 Legacy` → `/1967`.

### Mission and vision
**H2:** Our Mission

We create evidence-informed experiences that respond to real community needs, celebrate identity, strengthen belonging, and help people move forward with dignity, connection, and opportunity.

**H2:** Our Vision

We envision communities where people are seen, histories are honored, support is accessible, and every generation has opportunities to become the proof of what is possible.

*These concise web expressions are adapted from WBP's existing one-pager, not presented as a formal legal mission statement.*

### How the model works
**H2:** The Need. The Connection. The Proof.

**Intro:** We begin by listening, create experiences with intention, and learn from the people who take part.

**Card 01 — THE NEED:** Understand real community challenges, strengths, stories, and opportunities.

**Card 02 — THE CONNECTION:** Bring people together through culture, history, recreation, wellness, and experiences built around belonging.

**Card 03 — THE PROOF:** Track reach, learning, and participant experiences. Use the findings to make the next experience better.

*Framework note for coder: Earlier WBP one-pager labels the third phase “The Impact.” The website should use the user-selected “The Proof,” while describing measured participant experiences accurately—not claiming scientifically proven causation.*

### Why it matters
**H2:** Connection Is Not a Luxury

Belonging and meaningful connection matter to well-being. Our work brings history, learning, community resources, culture, and everyday joy together—without turning every experience into a lecture.

**Small research citation below this section (not a hero statistic):** A CDC analysis of 2022 data from 26 states found that 32.1% of surveyed adults experienced loneliness and 24.1% lacked social and emotional support. These are background data, **not** results achieved by WBP.

Source: https://www.cdc.gov/mmwr/volumes/73/wr/mm7324a1.htm

### Explore the stories
**H2:** Stories Behind the Proof

**Tile 1 — 1967: The Championship That Changed the Game:** Meet the WSSU Rams, Coach Clarence “Big House” Gaines, and Earl “The Pearl” Monroe. **Link:** `Explore the 1967 Legacy` → `/1967`.

**Tile 2 — Amir Is Still Unhoused:** Explore how the Morrill Acts, educational access, and today's student housing challenges raise questions about what it really takes to thrive. **Link:** `Explore Amir & the Morrill Acts` → `/amir`.

### Closing statement
**We celebrate who you are, honor who you've become, and invest in who you're becoming.**

---

# PAGE 2 — 1967 CHAMPIONSHIP LEGACY
**Route:** `/1967`

**Layout order:** Archival image + large “1967” hero → 3 stat tiles → Coach Gaines story → Earl Monroe story → why we teach this history → archival photo gallery → source links/footer.

**Image files:** `19510.jpg`, `19512.jpg`, `19514.jpg`, `19517.png`, `19521.jpg`. Supporting graphics: `WBP_60_Years_Original_Photos_Corrected.png`, `We Became the Proof 60 Years.png`, `Celebrating 60 Years CIAA to NCAA.png`, `We Became the Proof Magic Lives On.png`. Use authentic images, not AI recreations. Until an individual photo is positively identified, use neutral captions (e.g. “WSSU 1967 championship archive”) rather than assigning names.

### Hero
**Eyebrow:** WSSU HISTORY · 1967

**H1:** The Championship That Changed the Game

In 1967, Winston-Salem State's Rams won the NCAA College Division men's basketball national championship—the first NCAA men's basketball national title won by a historically Black college or university.

### Numbers that tell the story
**H2:** A Season for the History Books

- **31–1:** The Rams' season record.
- **77–74:** The championship-game victory over Southwest Missouri State.
- **FIRST:** The first HBCU to win an NCAA men's basketball national title.

A championship is bigger than its final score. The Rams brought national recognition to excellence already flourishing at Winston-Salem State.

### The people
**H2:** Clarence E. “Big House” Gaines

Coach Gaines built a WSSU basketball program defined by discipline, mentorship, and extraordinary achievement. He led the Rams to the 1967 championship, shaping a legacy that reached far beyond the court.

**H2:** Earl “The Pearl” Monroe

Vernon Earl Monroe starred on WSSU's historic championship team. His creativity, scoring, and basketball brilliance helped carry the Rams to the national title and preceded his celebrated professional career.

### Why it matters
**H2:** More Than a Championship

Students deserve to know whose shoulders they stand on. The 1967 Rams offer a story of HBCU achievement, collective excellence, determination, and possibility. Their history can inspire curiosity and deepen pride in the communities that produced them.

### Sources — visible at bottom
- WSSU 1967 championship team: https://wssurams.com/honors/c-e-big-house-gaines-hall-of-fame/1967-ncaa-championship-basketball-team/107
- WSSU 2026 history (NCAA College Division, predecessor of today's Division II): https://wssurams.com/news/2026/8/6/general-wssu-to-induct-2026-clarence-e-big-house-gaines-athletic-hall-of-fame-class.aspx
- WSSU Earl Monroe biography: https://wssurams.com/sports/2022/4/11/about-hall-of-fame-Hall-of-Fame-Bios-Earl-Monroe-Bio.aspx

**Rights note:** Historical photos, school marks, and personal likenesses may have separate usage rights; include source attributions and don't imply an official WSSU endorsement or licensing agreement.

---

# PAGE 3 — AMIR IS STILL UNHOUSED / THE MORRILL ACTS
**Route:** `/amir`

**Layout order:** Amir original artwork hero → 1862/1890 timeline → access versus thriving section → housing insecurity question → reflective close → primary sources/footer.

**Hero artwork:** `Amir Is Still Unhoused Graffiti Logo.png`. Amir is a **narrative symbol** of students experiencing housing insecurity; do not write a biography or attribute personal facts to a real student. Do not generate a photo purporting to depict Amir.

### Hero
**Eyebrow:** THE NEED · THE HISTORY · THE QUESTION

**H1:** Amir Is Still Unhoused

What does access to education mean if a student still lacks the basic stability needed to learn, belong, and thrive?

Amir represents a question, not a claim about one identified person's life.

### History of access
**H2:** How Land-Grant Education Began

**1862 — The First Morrill Act**

The Morrill Act used federal land grants to help states establish colleges focused on agriculture and mechanical arts. It expanded educational opportunity for many people, but Black students were often excluded by racial barriers. The original land-grant system was also built on Indigenous land dispossession, a history that must not be erased.

**1890 — The Second Morrill Act**

The Second Morrill Act required states receiving specified federal land-grant funds to admit students without racial discrimination or maintain separate land-grant colleges for Black students. It helped create and support historically Black institutions while permitting a segregated system whose resources were not always equal.

### From access to stability
**H2:** Access Is Only the Beginning

A college seat is not the entire promise of education. Students also need safe housing, food, connection, support, and the conditions to focus on learning. Historic racial exclusion and present-day student homelessness are distinct issues, but studying them together helps us ask a necessary question: **Who has the resources to fully participate in an education?**

**H2:** Why “Amir Is Still Unhoused”?

This campaign connects educational history with the realities of student housing insecurity. It asks communities to look beyond admissions and enrollment figures and recognize dignity, belonging, and stability as part of opportunity.

### Close / invitation
**H2:** What Does a Student Need to Thrive?

More than admission. More than a classroom. Stability, belonging, access, and people committed to making room for them.

**Closing statement:** The proof isn't simply that we got in. It's what we build so the next student can stay, learn, and thrive.

**Link:** `Return to Our Mission` → `/`.

### Sources — visible at bottom
- National Archives, Morrill Act 1862 and history of 1890: https://www.archives.gov/milestone-documents/morrill-act
- USDA NIFA, 1890 land-grant institutions: https://www.nifa.usda.gov/grants/programs/1890-land-grant-institutions-programs
- U.S. Capitol Visitor Center, Black/white college funding allocations under the Second Morrill Act: https://www.visitthecapitol.gov/artifact/division-agricultural-fund-between-white-and-colored-schools-1892-93

---

# BUILD REQUIREMENTS AND ASSET MAP

| Page | Assets to use | Placement |
|---|---|---|
| All | `WBP_Official_Transparent_Logo.png` or `01_WBP_Brand_Logo.png` | Consistent header |
| Home | `We Became the Proof Triptych.png`; `WBP The Need Banner Preview.png`; `WBP The Yard Banner Preview.png` | Hero / three-phase visual / story section as legibility allows |
| 1967 | `19510.jpg`, `19512.jpg`, `19514.jpg`, `19517.png`, `19521.jpg` | Real historical-photo gallery |
| 1967 | `WBP_60_Years_Original_Photos_Corrected.png`; `We Became the Proof 60 Years.png`; `Celebrating 60 Years CIAA to NCAA.png`; `We Became the Proof Magic Lives On.png` | Secondary information panels |
| Amir | `Amir Is Still Unhoused Graffiti Logo.png` | Hero |

**Implementation:**
1. Ship a fully responsive, accessible three-page website with equal design and functional priority for phone, tablet, laptop and desktop screens, using the actual copy above, clear headings and nav, compressed assets, descriptive alt text, keyboard-friendly controls, standard SEO titles/descriptions and link previews.
2. Each page's information must remain editable by the team. Provide source code/deployment details and a short, plain-English updating guide.
3. Cite the historical sources on their respective educational pages. Verify rights before public use of archival photos, logos, or personal likenesses; do not fabricate replacement images or claim partner endorsement.
4. Use no fake statistics, fabricated quotations, donations or contact forms that do not work. Leave future impact statistics for an evidence-backed update.
5. Keep **We Became the Proof** visually primary. A small footer may credit **Thoughts 2 Lyfe** as a supporting organization; do not create a separate T2L brand page.

**Suggested footer copy:** We Became the Proof — Honoring Stories. Creating Opportunities. Strengthening Communities. An independent community initiative supported by Thoughts 2 Lyfe.

**Team contacts after 11 a.m. November 3:** Fatima Mann — Director of Operations, timelines/implementation; Maya Monroe — partnerships and coordination; Crystal Branson — Executive Administrator, documents and follow-up. Ade — site implementation and technical handoff.

## Evaluation background (developer context, NOT homepage essay)
Our program logic is **The Need → The Connection → The Proof**, grounded in community insight and research about social connection and belonging. A short post-event survey can report participant counts, awareness of WSSU's 1967 history, activities engaged in, and *self-reported* changes in mood or connection. With approximately 25 voluntary respondents, findings remain descriptive pilot feedback, not a representative population estimate or proof of causal efficacy. Avoid publishing uncollected outcomes. Source: https://www.cdc.gov/mmwr/volumes/73/wr/mm7324a1.htm

**Handoff acceptance:** One working three-page site, WBP-native styling, all text present, source citations, authentic images and editing directions. No new creative brief required.
