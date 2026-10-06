# Atharva Rane — Portfolio (Framer)

Source of truth for the copy and structure of Atharva Rane's UX portfolio, built in Framer from the
Figma file *Babita-folio* (four projects). The site itself lives in the Framer project; this repo
keeps the content, image sources and the open to-do list.

- **Who:** Atharva Rane — 4th-year UX design student, MIT Institute of Design (MITID), Pune
- **Template:** Framer portfolio template (white UI, Inter, lime `/Other/Brand` accent)
- **Figma source:** `SNYsK9MlSSd8Xy6tjwaOVU` — sections *Service design*, *Social Psychology*,
  *Design Management*, *Semantics and semiotics*

## Site map (what was built in Framer)

| Page | Status |
| --- | --- |
| `/` Home | Rewritten: hero name + intro, About, **Selected work** (4 cards linking to the case studies), **Experience & education** (experience left blank), template CTA |
| `/projects/foodflow` | New case study — Service Design |
| `/projects/irreversibility` | New case study — Social Psychology / behavioural research |
| `/projects/fitsync` | New case study — Design Management |
| `/projects/object-archive` | New case study — Semantics & Semiotics |
| `/works/work-grid`, `/works/work-list`, `/works/:slug` | Template CMS pages; the *Works* CMS now holds the 4 projects (template items set to draft) |
| `/about`, `/contact`, `/journal`, Footer, CTA, Navigation | **Not edited** — see "Still to do" |

Every case study follows the same story arc: hero + meta (context, team, methods, outcome) →
problem → research → insight → reframe (dark band) → solution → value/evidence → reflection →
next project. Case-study text styles live under `/Case/*` in Framer.

## Still to do (in Framer)

1. **Experience** — Home › *Experience & education* › two `Role — Company` rows are placeholders.
2. **Image placeholders** (grey boxes labelled "Image placeholder"):
   - FitSync: hero image and three app screens (the app-screen frames in Figma are empty).
   - Irreversibility: toolkit session photos; Cost Ledger screen.
   - Object Archive: prototype walkthrough video.
3. **Navigation** (shared component — the Framer MCP could not edit it): change *Works* to link to
   Home › Selected work (or `/projects/foodflow`), hide or rename *Journal*, and update the Logo.
4. **About, Contact, Footer, CTA** — still contain template copy (name, email, socials). These
   pages/components could not be read through the Framer MCP; edit them directly in Framer.
5. **Breakpoints** — the four `/projects/*` pages only have a Desktop breakpoint. Add Tablet/Phone
   breakpoints and switch the 3–4 column grids to 1–2 columns.
6. **About photo** — the *3D Depth Cards* on Home still show the template image; drop in a portrait.
7. **Check facts** — name spelling (Figma credits "Atharva Rane"), degree title, project years,
   and team credits below.

## Project content

### 1. FoodFlow — Service Design (2026)
*A distributed surplus-food recovery system that turns a refused delivery from a dead end into a
meal for someone who needs it.*
- Team: Atharva Rane with Kunsh Sharma, Sanjeet Mohol & Passio Sylvester
- Problem: food is produced and value is created, then lost. Focus moment — a COD order refused at
  the door: sealed, fresh food with no owner, no pathway and no recovery protocol.
- Research: interviews with delivery partners, restaurant/cloud-kitchen owners and customers
  (22–45, 15–20 min each, directional); ecosystem, value-flow and as-is blueprint mapping.
- Personas: Rohan Sharma (22, student/intern), Sunita Yadav (38, domestic worker).
- Reframe: "What if surplus food didn't go to waste, but flowed through a system?"
- Solution: push notification within 60 s → in-app node map (≤ 800 m) → physical node (fridge,
  counter, tablet, human operator) → OTP handover + ₹30–50 rider credit → walk-in counter →
  recovery certificate, FSSAI FoSCoS record, CSR dashboard.
- Figma images used: 1:937, 1:835, 1:1159, 1:391, 1:948, 1:938, 1:930/936/942/933, 1:1456.

### 2. The Perception of Irreversibility — Social Psychology
*Why choosing a first major feels like a life sentence — and Reversibility Mapper.*
- Team: Atharva Rane with Kunsh Sharma & Passio Sylvester
- Landscape: 93% know 7 of ~250 careers; 1 in 10 get expert guidance; 73% start career talks with
  family; 50% from middle/lower-income homes fail employability benchmarks.
- Mechanism: structural → cultural → psychological pressures; irreversibility beliefs,
  catastrophic thinking, terror management, loss & regret aversion.
- 10 interviews (18–25; Design, BBA, Engineering, MBBS, BCom) → 7 themes.
- Generative toolkit: perception mapping, constraint-sensitivity probe, sentence completion.
  Insight: majors become psychologically final long before they are structurally irreversible.
- COM-B: opportunity is the primary deficit. Target segment: fear of switching / premature closure.
- Concept: Reversibility Mapper — Trajectory Archive + Cost Ledger, backed by prospect theory,
  decision aids, peer trajectories, descriptive norms, career narratives, trade-off transparency.
- Figma images used: 3:630, 3:469, 3:558, 3:638, 3:633.

### 3. FitSync — Design Management
*Your workout → your meal.*
- Problem: hostellers/migrants can't cook healthy; delivery ignores nutrition; trainer diets are
  costly and hard to maintain.
- Market: TAM ₹16,200 cr (FY24) → ₹37,700 cr (FY30), 15% CAGR; SAM ₹1,800 cr; SOM ₹180 cr.
- Solution: personalised macros, post-workout delivery, synced tracking; freemium app.
- Revenue: subscriptions, ₹150–250 single meals, ₹499/mo Premium, add-ons, gym commissions,
  trainer dashboard fees. Roadmap: MVP in 2 metros → wearables → gym partners → premium analytics.
- Figma images used: 1:5768, 1:5815, 1:6036.

### 4. The Object Archive — Semantics & Semiotics
*Narrating stories through objects.*
- Premise: "Not all stories are told with words. Some live in things."
- Approach: object as sign (signifier vs signified); archive language (volumes, dates, labels);
  contribution flow.
- Collections: Stone Sculpture, Broken Cutlery (Vol 17), Travel Archive, War Archive (Vol 15).
- Figma images used: 4:2016, 4:2545, 4:2563, 4:2580, 4:2595, 4:2015, 4:2665, 4:2900.
