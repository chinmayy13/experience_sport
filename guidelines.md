# Freelance Artifact Collection Project - Contributor Guide

## Overview

Unlike many Outlier projects, you are not asked to create new work. Instead, we are exclusively acquiring completed, high-quality deliverables that you have previously produced for real-world clients or personal professional portfolios.

The purpose of this project is to acquire existing, high-complexity deliverables (artifacts) created by experienced freelancers across various professional domains. We are purchasing genuine, pre-existing work to train and evaluate advanced AI models in replicating human-level professional tasks.

### Why are we collecting these artifacts?

AI models are becoming increasingly capable of performing professional tasks. To evaluate and improve these models, we need examples of real work completed by humans. Your submission may later be used to:

- Compare AI-generated work against real human work.
- Create evaluation rubrics.
- Build high-quality training datasets.
- Improve future AI systems.

For this reason, it is important that every submission reflects genuine professional work.

### What types of work are we looking for?

We are seeking comprehensive, production-grade deliverables across diverse fields (graphic design, architecture, video production, animation, audio, etc.)

To qualify, submissions must meet the following:

- Demonstrate advanced technical or creative skills beyond simple, entry-level tasks (multi-page architectural blueprints, complete brand identity packages, polished video edits, among others)
- Represent genuine work previously completed for clients or personal projects.
- Include necessary background details, client briefs, or original prompts so that the AI systems can attempt to recreate the final deliverable based on the initial requirements.
- Be submitted entirely in English.
- Contain editable outputs or source files generated using specialized software when necessary for review, editing, or verification purposes.

### PII Requirements

🚨 All personally identifiable information (PII) must be removed before submission, unless you own the rights to it or have explicit permission to use and sell it.

- **Audio**: Mute or beep any identifiable information, such as full names, brand names, or other personal details, unless you own them or have permission to sell/use them. NO copyrighted material.
- **All other domains**: Remove any PII that could identify a person, client, company, or brand (e.g. email addresses, phone numbers, street addresses, a real person named as the subject of the work, résumés/CVs, ID documents, passports), unless you own the rights to that information or have explicit permission to use and sell it.
- **Credentials**: Never include .env files, API keys, tokens, private keys, or credential files anywhere in the task (brief, inputs, or deliverables).

🚨 **Disclaimer**

If you have multiple similar projects, please upload only the ones you consider to be the most complex and the best match for our requirements.

Remember, we're looking for diversity across submissions, so prioritize showcasing a variety of project types and complexity levels.

🚨 **AI-Generated Content Disclaimer**

We understand that AI tools are part of many creative workflows. Minor assistance that does not produce content (e.g. spell-checking, noise reduction) is fine. However, the goal of this project is to collect human-created artifacts that reflect genuine creative and technical work.

Inputs and deliverables must not contain AI-generated content, in full or in part. Submissions with clearly AI-generated elements are rejected. The creative direction, execution, and final outcome must be driven by a person.

---

## Project Workflow

The workflow is simple:

1. Submit a complex, high-quality freelance project that you personally completed in the past.
2. Our team reviews the artifact to ensure it meets our complexity, originality, and completeness criteria.
3. If the submission meets our quality standards, it may move to the next stage of the pipeline.
4. Selected artifacts may later be used for rubric generation and AI training.

## What Should You Submit?

Each submission should represent one completed freelance project that you personally completed. To help reviewers accurately evaluate your submission, each project should include the following components:

Step 1 asks you to fill in five fields: Brief, Inputs, Deliverables, Domain, and Timeline. You will also accept the Consent to Data Usage and answer the Original Author Questions. Each item is explained below. Once submitted, your task runs through automated checks (see Automated Quality Checks).

### 1. Consent to Data Usage (Required)

Before submitting your artifact, you will be asked to review and accept the Consent to Data Usage statement. This consent confirms that you understand how your submission may be used within this project. It is required before you can submit your artifact. Please see below for more information:

> **Data Use & Payment Terms**: By submitting your work through this platform, you acknowledge and agree to the following terms. You will be paid for the time you spend submitting your project, provided your submission meets our brief requirements. If Scale and/or Outlier elect to approve your project for use, you will be entitled to additional compensation equal to the difference between the amount already paid for your submission time and the approved project amount. The approved project amount generally starts at a minimum of USD $50.00 and may reach up to USD $1,500.00, depending on the project's scope and complexity. By submitting your work, you grant Scale and Outlier the right to use, reproduce, modify, and otherwise manipulate the submitted materials; provided, however, that such materials will not be used until the applicable rubrics have been generated.

You confirm that you have read, understood, and agree to be bound by these terms before uploading your work.

### 2. Domain Selection (Required)

For every submission, you must select the domain that best matches the type of work you are submitting. Choosing the correct domain helps route your artifact to reviewers with the appropriate expertise and ensures it is evaluated within the proper context. The work described in your brief must belong to the domain you select.

Supported domains include:

- Graphic Design
- Audio & Music
- 3D Modeling & CAD
- Architecture & Interior Design
- Industrial & Product Design
- Game Development
- Animation & Motion
- Video Production
- Web & Interactive Development
- Data & Research
- Language & Documentation
- Marketing/Advertising
- Enterprise Comms (anonymized and redacted)

**Important Note:**

Audio & Music tasks: The content must be based on an existing audio file or use existing audio reference file(s) as input(s). Text-based briefs alone are not accepted for audio tasks.

### 3. Project Brief (Required)

The brief is a self-contained work order. Someone who has never seen your project should be able to read it, start immediately, and know exactly what a finished, acceptable result looks like. An AI model given only your brief and inputs should aim for the same result you delivered.

#### Required structure

Write the brief in Markdown using these four level-2 and 3 headings, spelled exactly as shown and in this order. Every heading must have content under it. Do not rename them (e.g. "Inputs", "Outputs", "The Task", "Assets").

```
## Work Description
### Requirements
## Provided Material
## Deliverables
```

Within each section, format freely: prose or bullets both work. For complex projects, group requirements under level-4 subheadings inside `### Requirements` (e.g. `#### Game Mechanics`, `#### Audio`, `#### Script`).

**1️⃣ ## Work Description**

One or two paragraphs stating what is being built and why: name the artifact, give essential context, and set the intent. Write in the third person with imperative openings ("Develop comprehensive architectural plans…"), neutral and concrete ("a four-unit consecutive townhome," not "a construction project").

**2️⃣ ### Requirements**

The constraints, standards, and acceptance criteria the result must meet (style, tone, length, dimensions, technical specs). Use a bulleted list of full, self-contained sentences with "should" or "must."

- No two statements may conflict (e.g. "landscape 16:9" and "9:16 vertical"), and none may be impossible on its own (e.g. "uncompressed MP3").
- Stated quantities must match what is listed. If you say "three options," list three.

**3️⃣ ## Provided Material**

An inventory of everything the worker receives: each file's path and a short description (e.g. "Cadastral floor plan (metric): input/cadastral_floor_plan.jpg"). If nothing is provided, write "None." Never leave it blank.

- Every uploaded input must be listed, and every listed input must be uploaded.
- Descriptions must match the actual files: a "voice note" must be an audio file, and a "lossless reference" cannot be an .m4a.
- References must be unambiguous. If you upload two images, don't just write "use the image."
- Don't contradict other sections (e.g. "None" here while Requirements says to start from a supplied file).
- Web and game projects: a folder of source files can be listed as one item (e.g. input/starter_project/), as long as nothing required is missing.
- Real-world freelancer test: include everything a freelancer would realistically receive for this job. Hiring a designer for new brand materials? Provide all current brand assets plus aspirational references (mood boards, reference photos, sketches).

**4️⃣ ## Deliverables**

A precise list of exactly what the worker hands back, each with its format and key specs (resolution, bit depth, duration, packaging). Describe the output, not just a file name: write "Final cinematic orchestral arrangement (WAV, 16-bit/48 kHz)," never "the final file" or "final.wav".

- Every listed deliverable must be uploaded, and every uploaded deliverable must be listed. No extras.
- The uploaded format must match the brief: MP4 means MP4 (not MOV), vector means .svg/.ai (not PNG), editable source means the layered native file (not a flattened export).

#### The two-expert test

If two experts could read your brief and produce results too different to compare against your deliverable, the brief is too vague. "Design a logo" could mean a wordmark, an icon, or both; "Model the chair" could mean a high-poly hero render or a game-ready asset under 10k triangles. Specify anything that changes the outcome. Details that don't change it can stay open (e.g. which CAD package to use, or exact shades within a stated palette).

#### NEW! Every requirement must be checkable

Rubric writers turn each requirement into a pass/fail check. If a reviewer cannot say whether a deliverable meets a requirement, the requirement cannot be graded. In practice:

- Use direct verbs. Avoid hedging verbs such as "explore", "consider", "try to", "if possible", and "feel free to". Use direct verbs instead ("incorporate", "use", "ensure").
- Label optional items explicitly. If something is truly optional, label it ("Optional: …") rather than softening the verb, so rubric writers can weight it correctly.
- Anchor subjective words. Subjective words ("bold", "playful") are fine as long as they are anchored to something concrete, such as a reference in the provided material, a measurable property, or a named example.
- Make deliverables exact. State the format and background (e.g. transparent vs. white) for each deliverable. Do not list duplicates or alternate filenames.

**Example**

- Before: Explore the use of black-and-white halftone facial elements.
- After: Incorporate at least one black-and-white halftone facial element (e.g. eyes, lips or teeth), in the style of the moodboard cut-outs.

#### Clean-copy rules

- Write the brief entirely in English.
- Use clean Markdown: no escaped characters (\#\# Work Description), no text cut off mid-sentence or mid-list, no placeholders (TBD, TODO, lorem ipsum, [insert]).
- Use file names without spaces; use underscores or hyphens (original_tune.mid, not original tune.mid). The name in the brief must match the uploaded file.
- No personal data or credentials anywhere in the task (see PII Requirements).

### Annotated examples

#### Example A: Short and simple (Audio & Music)

```
## Work Description

Using the provided lyrics and vocal melody demo, create a slow, romantic R&B song.
The production should include vocal harmonies performed in a soothing, deep voice.

### Requirements

- The song must use the provided lyrics and follow the melody in the demo.

## Provided Material

- Song lyrics: input/lyrics.txt
- Vocal melody demo (phone recording): input/vocal_melody_demo.wav

## Deliverables

- One complete, mixed, and mastered R&B song (WAV).
```

Why it works: the ask, input, and exact output format fit in a few lines. It also meets the Audio & Music rule: an existing audio file is included as input.

#### Example B: Checklist style (Audio & Music)

```
## Work Description

Create a cinematic orchestral cover of the provided tune for a fantasy short film.

### Requirements

- The cover should feel emotional and nostalgic.
- The tune should be reinterpreted for full orchestra using modern virtual
instruments.
- The arrangement should begin gently and build to a mild epic feel.
- The piece must be 2–5 minutes long and loop seamlessly as background music.

## Provided Material

- MIDI track of the original tune: input/original_tune.mid

## Deliverables

1. Final orchestral arrangement (WAV, 16-bit/48 kHz).
2. The same arrangement (MP3, 320 kbps).
```

Why it works: a scannable list that separates creative constraints from technical exports.

#### Example C: Graphic Design

```
## Work Description

Design a modern, minimalist logo for a specialty coffee shop named "Morning
Routine." The logo is a combination mark: a simple abstract symbol paired with the
shop name set in type.

### Requirements

- The logo must use a monochrome palette (black, white, or greyscale).
- The logo must stay legible at very small sizes, such as social media avatars.
- The logo must not use generic coffee cup or coffee bean icons.

## Provided Material

- Reference board of preferred aesthetics: input/reference_board.pdf

## Deliverables

- Vector source file of the logo (SVG).
- High-resolution transparent PNG of the logo (300 dpi, at least 2000×2000 px).
```

Why it works: "combination mark" removes the biggest ambiguity (wordmark vs. icon), and naming one vector format (SVG, not ".ai or .svg") leaves no doubt about what gets uploaded.

#### Example D: Grouped requirements (Game Development)

```
## Work Description

Develop a WebGL game in which the player is a bird sliding over a hilly landscape,
trying to land as many jumps as possible without crashing. The game is a relaxed,
retro-styled take on the hill-sliding genre (similar in feel to Tiny Wings).

### Requirements

#### Game Mechanics

- Holding the speed input (mouse button, X key, or Z key) makes the bird
accelerate on the ground and launch off the next hill.
- A jump succeeds when the bird lands on the downslope of a hill and gains
momentum; it fails when the bird hits the upslope and loses momentum.
- Each successful jump plays a positive sound and adds 1 to the jump counter.
- As the jump count increases, the bird gains a rainbow trail.

#### Audio

- Background music should be an 8-bit, chill/lo-fi melody.
- A positive sound plays on each successful jump and a crash sound on each failed
jump.

## Provided Material

None.

## Deliverables

- Full source code of the game (HTML, JavaScript, and CSS files).
- WebGL build with an index.html entry point that runs in current desktop
browsers.
```

Why it works: level-4 groups (Game Mechanics, Audio) keep a larger spec organized while keeping the four required headings. Naming another game as a style comparison is fine; reproducing its assets is not.

### 4. Inputs (Optional)

Inputs are the materials the work was based on: client assets, raw footage, templates, reference images, sketches. Upload every input listed under `## Provided Material`, and nothing that isn't listed. Each input must open, be complete, be of usable quality (not low-resolution, corrupt, or empty), and be original human work. If your project had no inputs, leave this empty and write "None" under `## Provided Material`. (Audio & Music tasks always require an audio input.)

### 5. Final Deliverable (Required)

The Final Deliverable is the completed work produced for the project. This should represent the final version of the work rather than drafts or intermediate versions.

Examples include:

- Graphic designs
- Logos
- Presentations
- Videos
- Audio
- 3D models
- Games

**IMPORTANT**: Upload every file listed under `## Deliverables`, no more and no less. Each file must open, be complete, be of usable quality, and match the format stated in the brief. Include editable source files.

Input files and deliverables across the dataset may use any of the formats below.

- **Documents**
  - Text: .txt, .json, .yml, .py, .js, .ts, .css, .java, .go, .php, .rb, .swift, .sql, .sh, and other common source code files. Any non-binary file not otherwise supported is displayed as text.
  - Formatted: .md, .html, .pdf, .tex (LaTeX), and .ipynb (Jupyter Notebooks).
  - Spreadsheets: .csv, .xls, .xlsx.
  - Microsoft Office: .ppt, .pptx, .doc, .docx.
- **Media**
  - Images: .jpg, .jpeg, .png, .gif, .bmp, .webp, .svg, .ico, .avif, .tif, .tiff.
  - Video: .mp4, .m4v, .mkv, .webm, .mov, .avi, .wmv.
  - Audio: .mp3, .wav, .ogg, .aac, .m4a, .midi, .mid.
- **Design & 3D**
  - Design: .psd.
  - 3D Models: .obj, .mtl, .stl, .gltf, .glb.
  - Autodesk/CAD: .dwg, .dxf, .skp, .stp, .step, .ipt, .3dm, .3ds, .fbx, .rvt, .ifc, and other formats supported by the Autodesk Viewer.
- **Data & Interactive**
  - Databases: .sqlite, .db.
  - Websites/WebGL: Interactive builds with .html entry points and associated .js and .css assets.
  - Anki: .apkg (limited to front and back card formats).

### 6. Original Author Questions (Required)

You must also answer the following questions about your submission:

1. What did the client request?
2. What are all the reasons this is a great deliverable?

### 7. Project Timeline (Required)

When tasking, you must also select the option that best describes how long this freelance project took to complete:

- Less than 2 hours
- Single-day (3–8 hours)
- Multi-day (1–3 days)
- Project-scale (3–14 days)
- More than 14 days

**Important**: Everything you submit must be de-identified. Remove all personally identifiable information (PII) and any business-related information unless you own the rights to it or have explicit permission to use and sell it, and translate all submitted content into English before uploading.

---

## Automated Quality Checks

After you submit, your task is checked automatically in two passes. 1 - flagged issues block the task until fixed. 2 - warnings don't block it, but reviewers check the same criteria, so resolve them before submitting.

### ⚠️ (fix before submitting)

| Check | Fails when… |
|---|---|
| Brief Structure | One of the four headings (Work Description, Requirements, Provided Material, Deliverables) is missing, renamed, or empty. |
| Brief Integrity | The brief has escaped Markdown (\#\#), text cut off mid-sentence or mid-list, or placeholders (TBD, TODO, lorem ipsum, [insert]). |
| Brief Language | The brief is not predominantly English. |
| Input Resolution | The brief mentions an input that isn't uploaded, an uploaded input isn't accounted for, or the brief says "None" while inputs are uploaded. (Web/game: a folder reference is fine if nothing required is missing.) |
| Input Fidelity | An input is corrupt, empty (0 bytes), incomplete, low-resolution, or otherwise unusable. |
| Deliverable Fidelity | A deliverable is corrupt, empty (0 bytes), incomplete, low-resolution, or otherwise unusable. |
| Credentials | .env files, API keys, tokens, private keys, or credential files appear anywhere in the brief or files. |

### Check Flagged when…

| Check | Flagged when… |
|---|---|
| Brief Ambiguity | The brief deliverable line does not say what output is expected. The brief deliverable is described only by what the work involved, with no stated output. It is impossible to distinguish which upload to use based on the brief alone (Ex: "use the image" — fail if more than 1 image is uploaded because we do not know which one to use). The brief and materials are so ambiguous that two experts could produce deliverables too different to compare against the golden output |
| Brief Consistency | Two statements conflict, a statement is impossible (e.g. "uncompressed MP3"), a stated quantity doesn't match the list, or sections contradict each other about what is provided. |
| Input Accuracy | An input doesn't match its description or stated properties, or doesn't provide what the brief says it does. |
| Deliverable Accuracy | The uploaded format differs from the brief (e.g. MOV instead of MP4), or the file type can't be what's described (vector delivered as raster, editable source delivered flattened). |
| Safety: PII | Emails, phone numbers, street addresses, a real person as the subject of the work, CVs, ID documents, passports, or similar appear anywhere in the task. |
| AI-Generated Content | Inputs or deliverables are clearly AI-generated, fully or in part. |

### 🔍 Also checked by reviewers

- **Domain Match**: the selected domain is the best available fit for the work.
- **Deliverables Resolution**: every deliverable named in the brief is uploaded, and nothing extra is.
- **Brief Adherence**: the deliverable meets every explicit requirement of the brief (and ideally the implicit ones).
- **Third-party IP**: a real brand's logo, wordmark, or trade dress reproduced in the deliverable is flagged. Mentioning a brand as a style reference is fine.

---

## Task Types

| Category | Task Types & Descriptions |
|---|---|
| **Graphic Design** | Retail packaging design (existing) · Apparel/product technical flats & tech packs (existing) · Brand identity systems — logo suite, color/type system, brand guidelines PDF · Editorial/print layout — magazine spread, annual report, book interior · Label & packaging — compliant labels with nutrition panels, barcodes · Large-format graphics — trade show booth, vehicle wrap · Marketing collateral — pitch decks, one-pagers, social ad sets · Icon/illustration systems — cohesive vector icon sets · Print production prep — press-ready prep (bleed, imposition) |
| **Audio & Music** | Original music production (existing) · Sound design (existing) · Mixing & mastering — multitracks to mastered master · Podcast/dialogue — raw recording to cleaned episode · Jingle/sonic branding — audio logo with variations · Implementation — sound-to-picture or middleware sessions · Sample pack design — themed one-shots, loops, synth banks · Remix/edit — radio edits, instrumental/acapella versions · MIDI orchestration — lead sheet to full arrangement |
| **3D Modeling & CAD** | Production-ready CAD (existing) · 3D asset modeling (existing) · Hard-surface modeling — consumer electronics viz · Character sculpting — concept art to rigged mesh · Reverse engineering — scan to clean parametric CAD · 3D print optimization — supports, tolerance fits, build splitting · Photogrammetry cleanup — raw scan to optimized asset · Visualization scenes — materials + lighting to photoreal renders · CAD drafting — 2D to 3D model or format migration |
| **Architecture & Interior Design** | Construction drawings (existing) · Schematic design — concept plans and massing · FF&E packages — mood boards, furniture specs, budget · Renovation documentation — measured drawings to proposed plans · Permit sets — code analysis and zoning compliance · Kitchen/bath design — elevations and section details · Landscape plans — grading and planting plans · BIM modeling — 2D set to Revit model · Marketing renders — CD set to photoreal images |
| **Industrial & Product Design** | Functional product design (existing) · DFM revision — re-engineering for injection molding/CNC · Enclosure design — PCB to housing with component integration · Concept development — sketches to concept CAD/renders · Tooling design — assembly aid or test fixtures · GD&T packages — fully toleranced manufacturing drawings · Ergonomics redesign — redesign with anthropometric rationale · Assembly engineering — multi-part assembly with BOM |
| **Game Development** | Playable templates (existing) · Level design — greybox to playable level · Asset pipeline — high-poly to baked engine asset · Mechanics scripting — inventory, dialogue, or save systems · UI/HUD implementation — mockups to functional engine UI · Pixel-art — character sheets and animation cycles |
| **Animation & Motion** | Animated pieces (existing) · Logo stings — static brand to animated ident · Explainer videos — script to storyboard to synced VO · Kinetic typography — audio/script to type animation · Lottie/UI motion — micro-interactions and onboarding · Character animation — lip-synced gesture performance · Data-driven motion — CSV to animated charts · Broadcast packages — lower thirds and title templates |
| **Video Production** | Product/promo video (existing) · Editing — raw rushes to graded deliverable · Social repurposing — long-form to shorts/reels · Color grading — log footage to graded output · Event videos — multicam to highlight reel · VFX/compositing — green screen and cleanup · Trailer editing — asset library to trailer · Localization — subtitles and versioned exports |
| **Marketing/Advertising** | Campaign concepting — brief to multi-channel campaign platform · Performance creative sets — static/video ad units · Paid social variant matrices — hook/copy/creative permutations built for A/B testing · Landing page + funnel copy — offer to conversion-optimized page with CTA hierarchy · Email lifecycle campaigns — built templates for different purposes · SEO content packages — keyword research to content briefs and long-form articles · Brand messaging & positioning — audience research to messaging framework · Media plan & flighting — budget to channel allocation with reach/spend projections · Campaign reporting — raw platform data to performance deck with recommendations · New-business pitch decks — RFP to full creative pitch presentation |
| **Enterprise Comms (anonymized and redacted)** | Executive communications — leadership announcement, all-hands script, town-hall deck · Org change & restructuring comms — rollout plan with FAQs and manager talking points · Crisis & incident comms — holding statement, escalation notice, post-incident update · Policy & process rollout — policy document to employee-facing guide and comms plan · Investor & board materials — quarterly board deck, shareholder letter, earnings narrative · Press releases & media kits — announcement to release, boilerplate, and media Q&A · Internal enablement content — employee handbook, benefits guide, onboarding curriculum · Proposals & RFP responses — requirements to structured proposal or SOW · Newsletter & intranet content — recurring internal newsletter or intranet article series · Executive ghostwriting — LinkedIn posts, op-eds, keynote remarks in a leader's voice |
| **Web & Interactive Development** | UI screens & kits (existing) · Design-to-code — Figma to responsive HTML/React · Landing pages — copy/assets to designed page · Design systems — tokens and component libraries · Interactive prototypes — clickable Figma/Framer · Email design/build — designed + coded HTML email · Dashboard UI — data schema to dashboard components · Accessibility — WCAG-compliant remediation |
| **Language & Documentation** | Localization — translated content → market-adapted version (units, idioms, currency, cultural references, legal disclaimers) · Captioning & subtitling — video → SRT/VTT captions, synced and formatted per platform specs · Proofreading & copyediting — draft document → polished version with tracked changes and a style-consistency pass · Technical writing/documentation — product/feature spec → user guide, API docs, or knowledge-base article · Contract & legal document review — draft contract → redlined version with risk flags and plain-language summary of key terms · Ghostwriting — outline/interview notes → finished article, speech, or long-form piece in a specified voice · Document format conversion/migration — legacy or scanned document → clean, structured digital file (OCR'd PDF → Word, or legacy format → modern format) · Glossary & style guide creation — brand/product content → standardized terminology glossary and writing style guide for consistency across translators/writers |
| **Data & Research** | Market/industry research reports — brief + topic → structured research report with sourced findings, competitive landscape, and citations · Survey design & analysis — research question → survey instrument, then raw response data → statistical analysis and findings summary · Data annotation/labeling — raw text/image/audio corpus → labeled dataset per a defined taxonomy or labeling guide (classification, NER, bounding boxes, etc.) · Statistical/quantitative analysis — raw dataset + research question → analysis (regression, hypothesis testing, cohort analysis) with charts and a written interpretation · Dashboard & data visualization — dataset + KPIs → interactive dashboard (Tableau/Looker/Power BI) or chart set with narrative insights · Literature review & synthesis — set of papers/sources → structured synthesis with themes, gaps, and citation list · Forecasting & modeling — historical dataset → predictive model with methodology writeup and validation metrics · Fact-checking & source verification — claim or document → verified/annotated version with sourcing and confidence ratings · Competitive intelligence teardown — company/product name → structured comparison matrix (pricing, features, positioning) from public sources |

---

## Examples of Approved Work

Each brief below follows the structure in Section 3.

### Architecture & Interior Design

**Brief**

```
## Work Description

Please design the following:
- Bathroom: 3 interior design options for the existing bathroom (wall-hung WC in
the indicated location).
- Apartment: 6 furniture layout options; pick one "final" option for detailed
plans.

### Requirements

- Cadastral notation is "room no. / gross area (meters squared)".
- Rooms in cadastral plan:
  - Rooms 27, 28, 29: habitable rooms
  - Room 26: kitchen
  - Room 26a: living room
  - Room 26b: veranda
  - Room 25: bathroom
  - Room 24: hallway
- There is a door from the living room to the veranda, as shown in
`input/additional_measurements.jpg`
- Dimensions in deliverables are design intent; contractor to verify all on site.

## Provided Material

- Cadastral floor plan (metric): `input/cadastral_floor_plan.jpg`
- Zoomed bathroom plan: `input/bathroom.jpg`
- Site photos: `input/bathroom_photos/photo_#_y.jpg`
- Additional measurements of the bathroom, living room, and veranda:
`input/additional_measurements.jpg`

## Deliverables

- Bathroom interior design - 3 options:
  - Renders: At least 1 view per option, at least 1200 pixels on long edge.
Include one render from the top (JPG)

- Furniture layouts - 6 options:
  - One PDF floor plan per option, imperial dimensions (feet-inches) for key
clearances and furniture sizes.
  - One consolidated DWG containing all options.

- CAD trace of cadastral plan:
  - Provide a clean DWG + PDF. Trace to scale, align walls, doors, windows
```

**Provided material images:**

![Cadastral floor plan](images/01_arch_cadastral_floor_plan.jpeg)
*Cadastral floor plan (metric) — `input/cadastral_floor_plan.jpg`*

![Zoomed bathroom plan](images/02_arch_bathroom_plan_zoomed.jpeg)
*Zoomed bathroom plan — `input/bathroom.jpg`*

![Additional measurements](images/03_arch_additional_measurements.jpeg)
*Additional measurements of the bathroom, living room, and veranda — `input/additional_measurements.jpg`*

**Reference Deliverable (site photos):**

![Site photo - shower curtain](images/04_arch_site_photo_shower_curtain.jpeg)
![Site photo - sink and toilet](images/05_arch_site_photo_sink_toilet.jpeg)
![Site photo - closet](images/06_arch_site_photo_closet.jpeg)

**Final Deliverable:**

![Final dimensional plan](images/07_arch_final_dimensional_plan.png)
![Final 3D render](images/08_arch_final_3d_render.jpeg)
![Furniture layout plan Option 1](images/09_arch_final_furniture_layout_option1.png)

### 2D Animation

**Brief**

```
## Work Description

Create a 2D animated video that explains and shows the process of trimming,
pruning, stump removal, and tree health maintenance. The video should educate
potential customers on the process and build trust in the brand through a short,
informative video.

### Requirements

- Audience: Homeowners, Real estate developers, Facility managers, Landscapers,
Anyone in need of tree maintenance or removal
- Tone: Professional yet friendly, instilling confidence and reliability
- Length: Around 60 seconds
- Visual Preference: Bold font, natural color palette (greens, browns, light
blues), nature-related icons and illustrations, subtle use of characters (e.g.,
workers, trees, property)
- Video style: Flat design / modern style, subtle transitions and motion graphics,
clean 2D animation, icon-based with light character use, no subtitles

### Script

Welcome to Skyline Tree Services, your trusted partner for all tree care needs.
And here's how we do it:
1. We start with a thorough consultation to understand your tree care needs.
2. Whether it's shaping your tree, pruning it, bracing it, removing a stump, or
grinding it, our experts conduct a detailed assessment of your tree's health and
structure.
3. We create a customized care plan tailored to each tree's specific requirements.
4. Using the latest technology and techniques, our skilled team performs the work
efficiently and safely.
5. At Skyline Tree Services, safety is our top priority. We ensure all precautions
are taken to protect your property and our team.
6. Once the job is done, we clean up thoroughly, leaving your space as beautiful
as we found it.
And here's how we work at Skyline Tree Services. Contact us and let us help you
care for your trees.

## Provided Material

- Raw voiceover audio file (`input/VoiceOver.wav`)

## Deliverables

- 2D animated video with audio from the provided voiceover (MP4, 1080p resolution)
```

*Reference Deliverable: Raw voice file*

*Final Deliverable: https://imgur.com/a/IvwFIGD*

### 3D Modeling & CAD

**Brief**

```
## Work Description

Provide a realistic 3D model of a gaming chair based on supplied reference images
and dimensional information. The objective is to accurately recreate the design
while maintaining production-ready quality suitable for use in a 3D content
pipeline. Texturing and animation are not part of the assigned scope of work.

### Requirements

All major components, including the backrest, seat, armrests, base, gas lift, and
wheels, have to be modeled as separate objects so they can be detached and rigged
if required.

## Provided Materials

Reference images provided in 'input/Reff01.jpg' to 'input/Reff17.jpg'

## Deliverables

1 FBX model (in .fbx)
1 OBJ model (in .obj)
1 Completed UV layouts (in .jpg)
12 Final rendered images in different angles and reclining positions (in jpg).
3 Wireframe model images (in jpg).
```

**Reference image and screenshot of the OBJ 3D model's deliverable:**

![Gaming chair reference photo](images/10_3dcad_gaming_chair_reference.png)
![Gaming chair 3D render](images/11_3dcad_gaming_chair_render.png)

### Graphic Design

**Brief**

```
## Work Description

Create a luxury, seamless floral background featuring golden chrysanthemums and
leaves on a dark teal background. The design on the provided sample is to be
replicated exactly as a starting point, and then extended.

### Requirements

- The provided image should be used as a base for the design to be developed,
continued, and expanded to include the details of the flower and complete the card
to the full size with leaves and other chrysanthemums.
- The card should have one almost complete chrysanthemum, and other chrysanthemums
around with a few leaves surrounding them.
- The pattern is to be developed as a seamless floral design pattern, meaning it
can be repeated continuously to cover a larger area.
- The leaves and flower petals should look like they are shiny.
- The final design should have a luxurious, rich look.
- The background should be entirely dark teal, as seen in the provided file.
- The flowers should be of a golden contour.
- The leaves should only be dark teal and black lines.
- The color palette is limited to the following colors: dark teal, black, and
gold.

## Provided Material

- `input/Sample.png`

## Deliverables

- Final pattern design as .PNG (4500 x 3000 px)
```

**Human Deliverable vs Model Deliverable:**

![Human deliverable - floral pattern](images/12_graphicdesign_human_deliverable.png)
![Model deliverable - floral pattern](images/13_graphicdesign_model_deliverable.png)

### Audio & Music

**Brief**

```
## Work Description

Create an educational podcast about Electrical Micro Grids. This podcast will be
broadcast on a marketing company's internal portal. The client wants the podcast
to be a short segment that covers current hot topics (news, new technologies,
practical topics, etc.). Each episode will treat a single topic.

### Requirements

- The intro and outro should be the soft moments of the provided music.
- The duration of the spoken explanation should not exceed 2 min 10 seconds.
- The overall duration of the podcast episode should not exceed 2 min 30 seconds.
- One narrator only, with a professional and calm tone and pace of voice.
- A radio presenter-type audio result is what the client is looking for.
- The final mix should enhance the tone and clarity of the voice and balance the
level of the music so that the voice is always prominent and understandable.
- The original vocal track provided as input contains many different types of
imperfections (e.g., hesitations, sighs, false starts, etc.) that should not be
present in the deliverable.
- It is acceptable to remove clicks and background noise if necessary, as long as
it does not affect the speech.
- Using reverb and additional mastering effects is acceptable if they enhance the
experience and the overall quality of the program, but not necessary.
- The final result should sound clear and professional.
- The final audio file must be delivered as a stereo WAV file, 48 kHz, 24-bit.

## Provided Material

- Raw (unedited and untreated) vocal recordings provided in `input/VOIX_04.wav`
- Raw music file (under CC0) provided in `input/oceanking-september-219737.mp3`

## Deliverables

- A single stereo 48 kHz 24-bit WAV file.
```

*Link to the folder with Input, Human deliverable, and Model deliverable*

### Payment Structure

Approved projects generally pay a minimum of $50, with the potential to earn up to $1,500 depending on the project's scope and complexity.

---

## Complexity Signals

### Audio & Music

Below are the parameters taken into account to determine whether the provided content is of interest for our project.

**Legend**

- Green: Always considered regardless of the brief type.
- Purple: Almost always considered, but may play a less critical role depending on the brief type.
- Orange: Not critical if missing, but a clear plus if present.
- Blue: Specific use cases only.

We can also accept audio projects in French, Spanish, and Portuguese.

**Composition & arrangement quality**

*Why*: These elements are not typically generated by models unprompted, so their presence confirms the brief forced non-default behavior.

- Originality: Polyrhythms / polymetric layering, complex or shifting time signatures (binary -> ternary mid-piece, 5/4,7/8, etc.), unusual chord modulations.
- Polyphony (especially in genres where it's atypical AND especially interesting in songs)
- Non-obvious structural choices (for instance - but of course, it's not exhaustive: Pink Floyd - The Great Gig in the Sky). An example of a musical composition with no lyrics, no verse-chorus, just a wordless vocal "improvisation".
- Number of simultaneous instrumental voices to track and reconcile: more voices means more complicated.

Important note: It is not mandatory for the work to contain any of the elements listed above, as some pieces of music may not meet any of these criteria and yet still be excellent.

That said, on the one hand, these criteria reflect a certain level of originality that we are looking for, and this is really an important factor for this project. We do not want the data to be flat or too easy to create, as that would defeat the purpose of the project. On the other hand, when these criteria or other types of truly original and unconventional elements are present and incorporated in an intelligent way, they are definitely a strong plus.

This actually applies to everything we are looking for: we want something professional, polished, and accomplished, with a certain level of originality and excellence. Ultimately, we are looking for something that makes the submission stand out and feel unique.

**Mixing & mastering**

*Why*: The audio quality of your final deliverable is always paramount.

- Note: For submissions where the input is the raw stems and the output is the finalized version:
  - Starting quality of stems: poor stems transformed into a clean, beautiful mastered track is always better because models are already good at standard mixing/mastering,
  - Degree of "color"/character change vs. pure technical cleanup: it's one thing to be able to clean audio artifacts from a track, but it's another that a master process proves creative, not just technical.

**Cross-cutting checks**

*Why*: This ensures that the brief provides a holistic challenge for the model.

- Does it combine multiple types of reasoning at once? (Not an automatic fail if it doesn't, but the deliverable would then need to be of an even better quality if it focuses on or tests a single or only a few areas)
- Is this something the model wouldn't attempt unprompted?
- Does it sound impressive to a human ear?
- Is it genuinely novel, or a variant of an already-oversubmitted task type (e.g. clean-stems-to-mastered, which is now something the models can do well).
- (only when relevant) Are raw/unprocessed inputs included so added value is provable?

**Acoustic timbre generation** (When acoustic instruments are present in the output)

*Why*: The more "purely acoustic" and multi-instrumental, the harder it is for a model to emulate convincingly.

- An acoustic rearrangement of a genre-specific song is a plus, because it adds a "transform" step on top of the timbre challenge

**Lyrics & vocals** (When lyrics are present in the input and/or output)

*Why*: Singing realism and conveying genuine emotion is often difficult even for humans.

- Lyrics-only input (model must invent melody/harmony) is challenging, but lyrics + harmony given in input also tests several aspects.
- Input = existing vocal material, brief: key transposition/reharmonization + new song based on this input: tests several aspects at once.

**Genre transformation & rearrangement** (When the brief requires a rearrangement)

*Why*: This requires analyzing and deconstructing the source, then rebuilding it with different timbres.

- The bigger the distance between source and target genre is, the bigger the challenge is.
- Alternate/reimagined versions: proves real transformation happened, not surface-level filtering.

**Sound design / SFX / Presets** (Especially important for electronic music, but relevant for many genres)

*Why*: This category identifies originality that a model or generic preset library wouldn't produce.

- Non-reproducibility/originality of the sound. Music producers are always looking for new presets. We're interested in that as well!
- Novel preset/one-shot/loop vs. common patch
- Demonstration material included to prove the sound is usable in context, not just a curiosity

**Quality of dialogue post-production**

*Why*: Relevant for podcasts, as it requires skills across sound production, engineering, and sometimes music production too.

- Editorial judgment: identifying bad takes and/or non-relevant to cut: this is the actual hard part, since models sometimes struggle to identify what content should be cut based on relevance only and not what's technically noisy

**AND**

- Number of separate elements integrated (raw recording, intro, outro, jingle): more pieces to reconcile into one coherent whole makes it harder.

**AND**

- Narrative coherence after cuts: proves the edit made sense contentwise, not just soundwise

**Audio Restoration** (Specific use cases only; currently a lower priority)

*Why*: The severity of the starting problem demonstrates the judgment required for the fix.

- Severity of original recording issues
- Amount of selective re-recording/editing required (vs. pure cleanup)
- Whether the result reaches genuinely release-ready quality

### Video Production

Below are the parameters taken into account to determine whether the provided content is of interest for our project.

**Filmed and Edited by a Human**

We do not accept any submissions that were totally created by AI from a combination of prompts and the submission of references.

We're looking for human-directed, filmed and edited work that you have produced for a client or a personal project matching professional standards. If some AI tools have been used in the process, it must be only in the framework of technical tools (like filling genAI to erase elements in After Effects tools for example) or for the fabrication of isolated layers present in the video like a plate to animate or a mate to replace the background for green or blue screen keyed videos.

**Professional Quality**

The quality of the submitted artifacts has to meet professional standards regarding the genre and the category of video. Submitted videos created for diffusion on social medias should be at least in 1080p resolution (square, portrait or landscape), the sound quality and levels have to meet as well the professional standards (without noise artefacts in the recording like excessive wind, saturation of microphones…), with a professional audio mix of a stereo soundtrack when several tracks are present (music, sound effects and voices properly mixed when present). For live recordings, parts of documentaries or magazines, the same requirements will apply, minimum 1080p resolution (in the rec.709 colorspace) and properly mixed stereo soundtrack for the deliverable. For cinematic and videos of ads, we will consider projects in UHD and 4k (in the rec.2020 color space) with priority versus HD ones and a proper stereo audio mix will be required as a minimum as well.

We expect totally post-produced artifacts, from edition to grading and mixing.

**Artifacts Duration**

We will limit the submissions to deliverables of a maximum duration of ten minutes.

**Accepted File Formats**

Please respect the following technical requirements, artifacts both in the (.mp4) or (.mov) encapsulation format with high bitrates H.264 or even better 10-bit HEVC (H.265) configuration will be accepted.

**Blur and Mute or Beep Identifiable Information**

Blur faces and remove any other identifiable information. Mute or beep any identifiable information, such as client names, brand names, or other personal details.

**Brief**

The submission of the artifact has to be completed by the upload of the brief provided by the client or the creative intentions you used if you are submitting a personal project. The brief shall also include detailed information that might influence the different post production steps when relevant: the main objectives of the video, the targeted audience (when available), the broadcast medium, title generation instructions, general grading style or references for the grading…

**Input Video Materials**

To complete the submission, you will upload when possible each individual complete video clip used or if not at least with significant handles regarding the part used in the final cut of your videos as Inputs.

**Sound Effects and Music Tracks**

When the final deliverable includes sound effects and commercial music tracks for which you don't own the legal rights outside the scope of diffusion of your video, please include indications in the brief for the model to recreate consistent audio tracks.

**Priority will be given to creative and style consistent projects**

We will prioritise projects with artistic direction and style that match with the objectives of the final video as defined in its brief and how it fits to its final broadcast medium (social networks, tv ads, documentary, fiction and so on.)

If you have multiple similar projects, please upload only the ones you consider to be the most complex and the best match for our requirements.

Remember, we're looking for diversity across submissions, so prioritize showcasing a variety of project types and complexity levels.

### Graphic Design

**Legend**

- Green: Always considered regardless of the brief type.
- Purple: Almost always considered, but may play a less critical role depending on the brief type.
- Orange: Not critical if missing, but a clear plus if present.
- Blue: Specific use cases only.

**Human created work**

Because we do not accept any submissions that were obviously created by AI.

We're looking for complex, human-created work that you have been paid for by a client (or a personal project you would consider worth being paid for).

**Type of Graphic**

Because some graphic types are easier to re-create for an AI model than others.

We're looking for rather difficult projects, to really challenge the model, and determine where it needs improvement. A few examples what we would consider rather difficult or rather simple:

*Rather difficult*

- Illustrations, especially hand-drawn
- Combinations of different elements (e.g. a logo that includes an animal wearing certain clothing or accessories instead of just an animal)
- Graphics based on actual photos (e.g. the client sent images that they wanted you to re-create as illustrations)
- Photo editing (e.g. taking elements from a photo, incorporating it into a different photo)

*Rather simple*

- Presentations
- Text-focused (e.g. a wordmark logo, business cards)
- Adding a simple text overlay to existing photos

**Resolution & Export**

Because the resolution and quality of your graphics is always paramount.

The quality must be consistent overall. We've seen cases where parts of the Deliverable were pixelated, blurry, or otherwise low quality, while the rest of it did not show any signs like these. Submissions that show clear signs of low and/or inconsistent quality are not eligible.

**Originality**

Because this makes the real difference in high quality submissions.

For example:

- Non-generic fonts
- Asymmetrical layouts
- Custom fonts (e.g. handlettered)
- Unexpected combinations of fonts
- Unexpected combinations of colors
- Custom icons, not from an icon library
- Actual photos instead of stock images
- Intentional use of space and empty room
- Self-created pattern instead of a template
- Micro details (e.g. only visible when zooming in)
- Amount of distinct elements and layer complexity
- Non-generic backgrounds (e.g. grainy, woven texture, watercolor style)

Please note: We are looking for highly complex, original contributions. So, the more it looks like a template or it was/could have been created using a template, the less likely it is eligible for our project.

**The more constraints, the better**

Because more constraints naturally mean more complexity.

The final output covers multiple layers of work, such as:

- Specific colors (e.g. hex codes)
- Specific dimensions (e.g. for package design)
- Scalability (e.g. for print products)
- Client's material needs to be incorporated (e.g. based on logo, corporate identity, …)

Please note: This does not mean that we generally don't accept projects that don't show many constraints, though it is more likely for a project to be eligible when showing natural complexity.

**Deliverables = not just one final graphic**

Examples:

- The client needs a logo. They want it as a JPG with light background, as PNG with transparent background, and as a vector graphic.
- The client requested different versions of the graphic (e.g. different target audiences, different flyer/poster designs for the same event)
- A set of graphics somehow connected to each other (e.g. Catalogue, Social Media Campaign)
- Different dimensions (e.g. Social Media → perfect dimensions for each platform)

**Print**

- Color mode is CMYK

**Vector Graphics**

- No embedded rasters

**Social Media**

- The dimensions of the output match the platform(s) preferred dimensions

**Consistency across multiple graphics**

- The exact same colors are used across various versions of a graphic.

### Architecture and Interior Design

Complexity factors in Architecture & Interior Design domain:

This classification details the technical and practical elements that make an architectural or interior design project complex enough and the following factors that represent the "nuances of the field" that professionals in the domain review and that standard systems frequently miss:

**1. Technical Coordination and Precision**

The complexity increases exponentially when it's requested to provide modifications/creation of specific objects on a scale:

- **Aesthetic Alignment**: Forcing a 1:1 spatial alignment between an interior furniture placement plan and an electrical socket plan (e.g., ensuring outlets, data ports, and switches align perfectly with desk placements, media centers, and beds without structural conflicts, including overlapping of elements that shouldn't).
- **Structural and Architectural Integration**: Requiring 3D models to strictly respect existing physical boundaries (column alignment and distance in between), load-bearing walls, and column locations provided in a 2D survey.
- **MEP and Fire Safety Coordination**: Integrating full Mechanical, Electrical, and Plumbing (MEP) systems with fire compliance (e.g., placing smoke detectors, wet-pipe sprinkler heads, and hydrant layouts to NFPA standards, calculating water pressure, and planning clear physical evacuation routes).

**2. Dynamic Structural Analysis & Mathematical Modeling**

Requiring structural standards with rigid rules:

- **Code-Compliant Material Specifications**: Applying exact engineering standards (for example, ACI-318 Strength Design or Uniform Building Code UBC-97) and specifying distinct concrete cylinder strengths (e.g., 5000 psi for load-bearing columns/shear walls vs. 3000 psi for foundation footings, basement walls, and slabs).
- **Finite Element Modeling (FEM)**: Translating physical layouts into 3D analytical models in engineering software.
- **Loading & Environmental Variables**: Calculating real-world environmental forces, including seismic parameters (response spectrum analysis, location factors, soil factor categories like SD, importance factors, and structural coefficients) and localized soil properties (such as allowable bearing capacities derived from geotechnical reports).

**3. Multi-Level Vertical Datums & Heterogeneous Inputs**

Synthesizing a massive, varied set of inputs to produce a single, unified, and accurate design system:

- **Sloped-Site Topography**: Resolving building volumes across complex sloped sites, requiring accurate vertical datums (e.g., foundation, finished floor levels, and roof elevations mapped precisely for spot elevations).
- **Media-to-Drafting Synthesis**: Multiple disjointed inputs, such as dimensional hand sketches, site photos, and CAD drawings, to build a single cohesive spatial design.

**4. Real-World Sourcing & 1:1 Execution Constraints**

- **1:1 Render-to-Product Sourcing**: Requiring that every furniture piece and decorative element displayed in a photorealistic 3D rendering correspond to an exact, currently available, off-the-shelf retail item (e.g., from IKEA or Amazon) with matching dimensions.
- **Zoning & Traffic Flow Optimization**: Balancing functional zoning (e.g., separating study, relaxation, and storage areas) within tight, physical dimensions, forcing the management of circulation pathways and visual openness. Additionally, the objects' placement in specific places for 2D floor plans in a modified input to produce a brand new floor plan usually triggers incorrect and inaccurate placement of elements (i.e., doors, windows, and walls).
- **Sections**: Accurately producing elevations and sections in specified spots of the floor plan along with correct measurements and structural details.

**5. Professional Nuances**

These are implicit expectations of industry-grade standards that are universally expected by professional evaluators of the domain:

- **Professional Pattern Tiling**: Ensuring that repeating textures, such as interior wallpaper designs or wall panels, tile seamlessly edge-to-edge, aligned and contained properly inside the perimeter established when rendered or printed at any scale. This is usually present in 3D modeling but can also happen in 2D floor plans where textures and design patterns are applied to floors or furniture.
- **Scale and Large-Format Legibility**: Designing environmental signage or set graphics (e.g., 2-meter-tall elements), ensuring graphic contrast and text legibility are optimized for distance viewing and TV broadcast limitations.
- **Production-Ready files**: Structuring the final CAD and BIM files for downstream professional use by providing the correct output formats (.DWG or .PDF). This includes organizing the output elements by name (using standard naming rules), adding the title block, setting up the plot styles, and preparing layout outputs ready-to-print.

### Web/App design

**LEGEND**

1. Green. Always considered regardless of the brief type.
2. Purple. Almost always considered, but may play a less critical role depending on the brief type.
3. Orange. Not critical if missing, but a clear plus if present.
4. Blue. Specific use cases only.

**DIFFICULTY SCALE**

1. Trivial. Rejected. A model produces this from the prompt alone.
2. Thin. Rejected. Real work, but no dimension a model struggles with.
3. Baseline. The accepted floor. Two hard dimensions present.
4. Substantial. Three hard dimensions, or two plus a measurable constraint.
5. Hard. Four or more, or three plus a genuinely non obvious domain.

**CROSS CUTTING CHECKS (1, Green)**

These apply to every submission, and exist to ensure the brief poses a holistic challenge rather than testing one narrow reflex. Ask whether the artifact combines multiple types of reasoning at once, which is not an automatic fail if it does not, though a narrow submission then has to be excellent in whatever it does cover. Ask whether this is something the model would not produce unprompted, or would not produce correctly on the first attempt. Ask whether a working engineer would recognise it as production work rather than a demo. Ask whether it is genuinely novel or merely a variant of an already oversubmitted task type, since dashboards, todo apps, landing pages and famous product clones are saturated and models handle them well. Finally, check that the original spec, ticket or client brief is included so the artifact can be graded against what was actually asked, and that raw or prior state inputs are included wherever added value needs to be provable.

An important note before the individual types. It is not mandatory for a submission to hit every criterion listed below, and some genuinely valuable artifacts will miss several while remaining excellent. That said, these criteria reflect the level of originality and difficulty the project needs, and flat data that is easily replicated defeats the purpose. When these elements are present and integrated intelligently rather than bolted on, they are a strong plus. What we are ultimately looking for is work that is professional, polished and accomplished, with enough originality that the submission stands out.

**WEB DEVELOPMENT, COMPOSITE (1, Green)**

Full site briefs are the most common real world request and the easiest to fake, so the bar is whether the layers are genuinely wired to each other. Count the number of build layers substantively touched, where three is the minimum: a real frontend, a real server enforcing rules, and real persistence. Check whether the state actually crosses those layers, meaning a change made in the interface reaches the database and returns correctly to other screens. Grade each layer against its own standards rather than letting a strong frontend carry the rest, and look for at least one irreversible or destructive action with proper confirmation and recovery. The whole thing must reproduce from a clean clone without undocumented local setup. On difficulty, a static site with a contact form is a 1, a frontend backed by a JSON file is a 2, three real layers serving a single role is a 3, multiple roles changing what each screen shows is a 4, and multiple roles combined with non obvious domain rules and a real external integration is a 5.

**FRONTEND DEVELOPMENT (1, Green)**

This is where most submissions land, and where the gap between polish and difficulty is widest. Look at the number of interconnected screens sharing mutable state and whether propagation between them is correct, at non standard interaction patterns such as drag to reorder, virtualised lists, canvas work or optimistic updates with rollback, and at whether state survives navigation and refresh rather than evaporating. Full keyboard operability is required, as are loading, empty and error states that are handled rather than assumed.

Technique depth in CSS is graded here and nowhere else (2, Purple). Utility frameworks encode every solved pattern, so difficulty begins exactly where the framework vocabulary runs out. Level A1 is expressible in stock utility classes. Level A2 is composed, covering multi step keyframes, clip paths, blend modes, masks and stacked gradients. Level A3 is spatially reasoned, covering three dimensional transforms with perspective, a coordinated light source, material simulation and computed geometry. Measure the framework escape rate, meaning the share of styling that cannot be written in stock utility classes, and confirm the technique is load bearing, since removing it must break the artifact rather than merely reduce its polish. A supplied reference image is required wherever a fidelity claim is made, so the result is measurable rather than argued. Decoration is not difficulty: hover states, transitions and shadows are quality bars, never complexity signals, and one decorative clip path does not make an artifact A2.

Structural scope in CSS is likewise graded here (2, Purple), because cascade architecture is a genuine engineering problem that grows with codebase size, unlike single component styling. Level B1 is a single component, B2 is a shared token system with theming, and B3 is cascade architecture under constraint. Require zero style leakage between components, with specificity conflicts resolved by layer order rather than importance flags, one token change propagating everywhere it should and nowhere it should not, and proof that a change to one screen does not regress another. On difficulty, a single page at A1 and B1 is a 1, a multiple component demo with no persistence is a 2, three screens with shared state at A2 or B2 is a 3, optimistic updates or offline capability on top of that is a 4, and A3 fidelity against a reference or B3 architecture in a large codebase is a 5.

**BACKEND DEVELOPMENT (1, Green)**

This is where domain logic lives, and derived rules are the single most reliable difficulty signal in the whole domain. The central question is whether business rules had to be derived from a written specification rather than recalled from convention, with jurisdictional tax logic, shift scheduling under legal rest constraints, inventory allocation across warehouses and prorated billing when a plan changes mid cycle all qualifying. Authorization must be enforced at the handler and never assumed from the interface. Errors should form a typed taxonomy mapped to status codes rather than generic server errors, mutating endpoints should be idempotent, multi step transactions should roll back cleanly, and concurrency and race conditions should be handled deliberately. On difficulty, create read update delete over one table is a 1, several endpoints with no authorization is a 2, role based authorization with real validation is a 3, derived domain rules plus transactional integrity is a 4, and derived rules combined with concurrency and event driven or scheduled work is a 5.

**DATA AND PERSISTENCE (1, Green)**

Schema quality is invisible in a screenshot and therefore rarely faked well. Constraints must be enforced at database level rather than in application code, migrations must be reversible and tested against seeded data rather than running forward only, relationship modelling should make invalid states unrepresentable rather than merely unlikely, and every index should be justified by a stated access pattern. Temporal or versioned data, soft delete that preserves referential integrity, and multiple tenants sharing one schema are strong additions when present (3, Orange). Migration over existing production data belongs to specific cases only but is a considerable plus wherever it appears (4, Blue). On difficulty, a single table is a 1, several tables with no constraints is a 2, a relational schema with real constraints and reversible migrations is a 3, the same with temporal data or multiple tenants is a 4, and the same with a production migration or a reporting layer across many joins is a 5.

**DESIGN AND USER EXPERIENCE (2, Purple)**

Design work is judged on completeness of thinking, since visual polish alone is highly reproducible. Every screen must ship with its empty, loading and error variants explicitly designed rather than implied, every flow must have both an exit and an error path with no dead ends, tokens must be defined as a system rather than hardcoded per screen, and each user role path must be drawn separately wherever roles diverge. At least one irreversible action with a designed confirmation and recovery state is a clear plus, as is dense data requiring genuine progressive disclosure decisions (3, Orange). On difficulty, a mood board or style tiles is a 1, high fidelity screens covering only the happy path is a 2, full flows with all states annotated is a 3, flows for multiple roles supported by a token system is a 4, and a regulated or high consequence domain where flow errors carry real cost is a 5.

**INTEGRATIONS (2, Purple)**

Third party systems fail in ways that cannot be imagined, only encountered, which is what makes this category valuable. The artifact should handle at least one genuinely awkward reality, such as token refresh mid flow, webhook delivery arriving out of order, reconciliation after a failed callback, or sandbox behaviour that diverges from production. Rate limits must be respected proactively rather than reacted to after a rejection, webhooks must be signature verified and idempotent under replay, and provider errors must be mapped to an internal taxonomy rather than surfaced raw. Multiple providers whose failures must be reconciled against each other are a clear plus (3, Orange). On difficulty, one unauthenticated API call is a 1, an authenticated client with no error handling is a 2, an authorization flow with refresh plus pagination and rate limiting is a 3, the same with idempotent webhooks and bounded retries is a 4, and reconciliation across multiple providers after partial failure is a 5.

**INFRASTRUCTURE (3, Orange)**

Infrastructure work is valuable when present but rarely the substance of a web brief on its own. Look for reproducibility from a clean clone with no undocumented local state, a rollback path that exists and has actually been executed rather than merely described, environments differing only by configuration, and secrets absent from the repository, with any exposure treated as a rotation rather than a deletion. Monitoring that demonstrably fires on an induced failure is a plus (3, Orange), while deploys with no downtime alongside concurrent schema changes belong to specific cases and are genuinely hard (4, Blue). On difficulty, one deploy script is a 1, a container definition with no pipeline is a 2, a continuous integration pipeline across multiple environments is a 3, the same with tested rollback and monitoring is a 4, and deployments with no downtime during a schema migration or across multiple regions is a 5.

**SECURITY (2, Purple)**

Security is only assessable against a stated threat model, and without one the word is an adjective rather than a test. A written threat model produced before the work is therefore non negotiable, because this criterion cannot function retroactively. Authorization must be verified on the server for every path and never implemented as hidden interface elements, input must be validated and output encoded with injection classes addressed structurally rather than filtered, and no sensitive data may appear in logs, addresses or client storage. Dependencies pinned and audited are a plus (3, Orange), while compliance driven requirements such as payment card or health data standards belong to specific cases and raise difficulty sharply (4, Blue). On difficulty, security headers added with no reasoning is a 1, basic input validation is a 2, a stated threat model with an authorization matrix is a 3, the same with attempted and defeated attacks documented is a 4, and compliance scoped work with isolation requirements is a 5.

**PERFORMANCE (3, Orange)**

A performance claim without a number is not a claim. A stated measurable target is mandatory, such as fifty thousand rows rendered at sixty frames per second, or a largest contentful paint under two seconds, and no target means no tag at all. Measurement must happen under realistic data volume and on the target device class rather than a development machine, optimisations must be justified by profiler output rather than intuition, and benchmarks from before and after the work must be included. A regression guard preventing silent decay is a plus (3, Orange). On difficulty, scattered memoisation with no evidence is a 1, an improved audit score with no target is a 2, a stated target met under realistic volume is a 3, the same with optimisation driven by profiler output and a regression guard is a 4, and a target met under adversarial load or on constrained devices is a 5.

**ACCESSIBILITY (3, Orange)**

Accessibility is easy to claim, easy to check, and consistently absent from model output unless explicitly demanded. A stated conformance level and named assistive technology are required. Every interactive path must be completable by keyboard alone, with focus always visible and never trapped, semantics must be correct before any assistive markup is introduced, and dynamic state changes must be announced to screen readers. All three verification passes are required rather than one standing in for the others: keyboard only, screen reader, and automated audit. Legally mandated contexts such as government or education belong to specific cases and make the artifact more valuable (4, Blue). On difficulty, alternative text alone is a 1, an automated audit score with nothing behind it is a 2, a stated conformance level met with full keyboard operability is a 3, the same with focus management across modals and route changes is a 4, and complex widgets made accessible where no standard pattern exists is a 5.

**CROSS PLATFORM (4, Blue)**

This is frequently claimed and rarely real, since responsive design is routinely mislabelled as cross platform work. Two or more materially different targets are required, rather than viewport widths. Capabilities must be detected rather than assumed, with no sniffing of the user agent string, input modality must be handled per target across touch, pointer and keyboard, and the shared core must be genuinely shared rather than two divergent copies. Parity must either be achieved or degradation must be explicitly documented per target, and each real target must be tested rather than simulated by resizing. On difficulty, a responsive page is a 1, a layout adapted for mobile is a 2, web plus a native shell with a shared core is a 3, the same with documented degradation per target is a 4, and divergent capability sets reconciled behind one interface is a 5.

**TESTING (3, Orange)**

The mutation check separates a real suite from a coverage number: deliberately break a business rule, and a test must fail. Beyond that, critical paths must be covered from end to end, failure and edge cases must be tested alongside happy paths, tests must be independent and free of order dependence with no shared mutable fixture, and the suite must run in continuous integration on every change. Tests that survive a refactor of the markup, because they assert behaviour rather than structure, are a plus (3, Orange). On difficulty, snapshot tests alone is a 1, high coverage over trivial paths is a 2, critical paths covered from end to end is a 3, the same with failure mode and edge case coverage is a 4, and concurrency, race and integration failure scenarios tested is a 5.

**TIMING WARNING**

Five of these criteria depend on a document that must exist before the work rather than after it: the threat model, the performance target, the accessibility conformance level, the cross platform target matrix, and the reference image for any fidelity claim. If any of them arrives after submission, it will inevitably be written to match whatever the artifact already does, and the criterion stops functioning as a criterion. All five should be required at intake.

### Game Development

**Legend**

- Green: Always considered regardless of the brief type.
- Purple: Almost always considered, but may play a less critical role depending on the brief type.
- Orange: Not critical if missing, but a clear plus if present.
- Blue: Specific use cases only.

**Gameplay Mechanics**

Does the game have game mechanics that would be complex enough for an AI to struggle to recreate, such as:

- Mechanics that rely on a moderate to complex physics system
- Ragdoll effects
- Moderate to complex enemy/NPC behaviours
- Multipart sequence events

**Level Design**

Does the level design have features that go beyond a basic setup, like a 2D platform linking from A to B? The level design should be cohesive across the board, AI can find it difficult to do or fit together in tandem with more complex game mechanics. Good examples of this would be:

- Environmental Challenges that require some level of critical thinking to overcome
- Multipart sequences to overcome a problem
- Obstacles that require a non default action to overcome (Example: requires a specific tool to progress, A Diamond Pickaxe to mine through Obsidian)
- Has points of interest that flow clearly from one to another, leading the player through the story in a way that shows clear design intent

**Functional UI**

Is the UI consistently functional in its use and repeated application. Some examples would be:

- Menu's Openable and Closable
- Functionality works consistently
- UI is resizable to fit multiple displays for its target application

**Coding Practice**

Do the programming elements follow solid programming principles, such as:

- Adding brief but detailed explanations on complex sections of code.
- Good memory management
- Avoid using tight coupling of classes or using monolithic approaches to classes
- Avoiding raw number values or inputs
- Clear and consistent naming conventions
- Avoids tying logic or game variables to FPS
- Avoids Poor or inconsistent state management.

**Optimisation & LODs**

Does the game have optimised assets to an industry standard I might expect to see. Some of the examples I would look out for are (3D Assets):

- Are there reduced poly LODs
- Created PBR textures
- Has the high poly model's topology been adjusted for a game ready low poly mesh
- Have the high poly details been baked

**Animation/Animation Controller**

Does the game have a cohesive and structured handling of animations and a good handling of states across all animators? For a good example, it might have things like:

- Ability to interrupt animations partway through to transition
- Animation blending between animation switches
- A state manager or similar system that handles the animation transitions
- Use of key frames within animation that represent milestones in the action (peak of a jump, attack impact frame)

**Consistency and Genre**

Does the game stick to the genre specifics of its brief, and does the design stay consistent and relevant over the course of the game? These are some of the things I'd be on the lookout for:

- Do the game's features and mechanics make sense when looked at as a full picture in relation to the game and game design principles?
- Does the game as a whole fit the genre description assigned in the brief, and does it have sub genres or additional elements that don't align?

**Game Robustness**

Does the game have setup safeguards and edge case catches that keep the player within the confines of the game itself? Some examples of these might be:

- Not allowing the player to leave the confines of a level
- Functional Progression when the level is completed in non standard ways
- The game isn't easily breakable through incorrect inputs

### Animation & Motion

Below are the parameters taken into account to determine whether the provided content is of interest for our project.

**Human directed Animation & Motion**

We do not accept any submissions that were totally created by AI.

We're looking for complex, human-directed and executed work that you have produced for a client or a personal project respecting the same professional standards. If some AI tools have been used in the process, it must be only for the fabrication of individual elements present in the video like a plate to animate or a mate for a background of your animation or motion video.

**Professional Quality**

Whereas you are submitting a 3D or a 2D animation, we are expecting your deliverable to meet professional standards such as a minimum 1080p resolution in square format, landscape or portrait, if in 1080p it should be in the Rec.709 colorspace and if UHD or 4K in the Rec.2020 color space. Each aspect of the animation should meet the expected standards of quality: well designed characters and objects, lighting, fluidity of the animations, mate paintings, interactions, consistent style between different elements, final render, grading, sound design when present.

**Brief**

The submission of the artifact has to be completed by the upload of the brief provided by the client or the creative intentions you used if you are submitting a personal project. The brief shall also include detailed information that might influence the different steps of the production when relevant: the main objectives of the video, the targeted audience (when available), the broadcast medium, the style of animation, general grading style or references for the grading…

**Artifacts Duration**

We will limit the submissions to deliverables of a maximum duration of ten minutes.

**Accepted File Formats**

Please respect the following technical requirements, artifacts both in the (.mp4) or (.mov) encapsulation format with high bitrates H.264 or even better 10-bit HEVC (H.265) configuration will be accepted.

**Warning**

If your animation includes some smoke effects, clouds, fire, dust or light or color gradients, you will absolutely want to avoid 8 bit videos which will introduce a lot of artifacts such as cross color, irisation and so on especially in 1080p which could severely harm the quality of the presentation of your work.

**Input Materials for 3D Animation and Motion**

You must complete your submission by providing the individual, starting elements used in the project as separate files:

- 3D Models: .fbx (preferred for rigged characters/objects) or .obj (for static props).
- Matte Paintings / Backgrounds: .exr or .pngr (high-resolution, flat files).
- 2D VFX Plates / Elements: (For smoke, fire, dust, or background crowds) Provided as .mov, .mp4 or a .png/.exr image sequence.
- Packaging: Put all these separate .png files into a single ZIP folder.

**Input Materials for 2D Animation and Motion**

You must complete your submission by providing the individual, starting elements used in the project as separate files:

- Format: Export each component as a transparent .png (do not use vector formats like .svg or .ai)
- Cropping: Trim each .png tightly around the asset boundaries to remove unnecessary empty transparent space.
- Packaging: Put all these separate .png files into a single ZIP folder.

**Sound Effects and Music Tracks**

When the final deliverable includes sound effects and commercial music tracks for which you don't own the legal rights outside the scope of diffusion of your video, please include indications in the brief for the model to recreate consistent audio tracks.

**Priority will be given to creative and style consistent projects**

We will prioritise projects with artistic direction and style that match with the objectives of the final video as defined in its brief and how it fits to its final broadcast medium (social networks, tv ads, documentary, fiction and so on.)

If you have multiple similar projects, please upload only the ones you consider to be the most complex and the best match for our requirements.

Remember, we're looking for diversity across submissions, so prioritize showcasing a variety of project types and complexity levels.

### Data & Research

This domain has a broad scope of tasks that can be sent, and will likely be the work of an expert in its field. Because of this, we are not expected to fully understand the expert's field of expertise, but rather to analyse if the models' are capable to fulfill the task.

**Project types in scope**

| Project type | Shape of the work |
|---|---|
| Market and industry research reports | Brief and topic in, a structured research report out with sourced findings, competitive landscape and citations |
| Research development tools | Development of a programming package that allows the simulation of complex fenomena, allowing research groups to develop new simulations and research. |
| Research paper analysis | A research task is sent, which requires analysis of an existing research or providing insight into expected results and outcomes |
| Survey design and analysis | Research question in, a survey instrument out; then raw response data in, statistical analysis and a findings summary out |
| Data annotation and labelling | A raw text, image or audio corpus in, a labelled dataset out against a defined taxonomy or labelling guide - classification, named entity recognition, bounding boxes |
| Statistical and quantitative analysis | A raw dataset plus a research question in, analysis out - regression, hypothesis testing, cohort analysis - with charts and a written interpretation |
| Dashboards and data visualisation | A dataset plus KPIs in, an interactive dashboard or chart set out with narrative insight |
| Literature review and synthesis | A set of papers or sources in, a structured synthesis out with themes, gaps and a citation list |
| Forecasting and modelling | A historical dataset in, a predictive model out with a methodology writeup and validation metrics |
| Fact-checking and source verification | A claim or document in, a verified and annotated version out with sourcing and confidence ratings |
| Competitive intelligence teardowns | A company or product name in, a structured comparison matrix out covering pricing, features and positioning from public sources |

**What we know applies today**

- Send the original research question or brief. Without it there is nothing to grade the output against.
- Send the raw dataset or source set you started from, not just the finished analysis.
- Deidentify. Replace identifying fields with realistic synthetic data that preserves format and distribution rather than deleting them, so the analysis stays reproducible.
- English throughout, including column names, labels and annotations.
- Include the working files - notebooks, query files, model code - not only the exported report.

**Is your project complex enough?**

Tier 1 does not exist in this domain. Single-day work is not complex enough for the project. Start at Tier 2.

| | Tier 2 - Multi-day | Tier 3 - Project scale | Tier 4 - Enterprise scale |
|---|---|---|---|
| **What puts it in this tier** | - Expert knowledge in an aspect that agents can not solve properly<br>- Semi-long deliverables (5 to 10 pages of documents, data that requires a somewhat complex and extensive analysis)<br>- Tests that evaluate at least a part of the project<br>- Unique analysis that covers part of the project, which agents fail to perform | - Expert knowledge in 2 to 3 aspects that agents can not solve properly<br>- Long deliverables (10-30 pages of documents, hundreds of MB of data that requires somewhat complex and extensive analysis)<br>- Complete tests that evaluate parts of the project<br>- Unique analysis that covers part of the project, which agents fail to perform | - Expert knowledge in 4+ aspects that agents can not solve properly<br>- Very long deliverables (30+ pages of documents, GB of data that requires complex and extensive analysis)<br>- Complete tests that evaluate the whole project<br>- Unique analysis that span over multiple aspects of the project, which agents fail to perform |
| **Typical client inputs** | Clear description of the required analysis or functionality, functional spec, initial assumptions and expected analysis | Same as before plus a reference analysis, existing simulations or analysis, extensive documentation | Same as before with more complex and extensive analysis or requirements |
| **Typical deliverables** | Document files covering the analysis with ample documentation. In case of simulations being needed, the full code to be run from console. | Same as before | Same as before |

### WIP Sections (Not Yet Detailed)

The following domain complexity-signal sections were marked as work-in-progress (WIP) in the source document, with no content provided yet:

- WIP 3D and CAD
- WIP Industrial & Product Design
- WIP Marketing/Advertising
- WIP Enterprise Comms (anonymized)
