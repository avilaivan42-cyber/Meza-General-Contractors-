# MEZA GENERAL CONTRACTORS — MASTER PROMPT
**Updated:** June 1, 2026 — Session 9 | **Status:** Single source of truth. Edits go here, not into new docs.

---

## CANONICAL SOURCE — GITHUB (read first)
> ✅ **SESSION 9 (June 1, 2026): repo `main` IS in sync + verified.** Latest commit `f227ff0`. The 5 production pages (index/about/commercial/contact/insurance-claims) + **13 optimized WebP photos at repo ROOT** are committed. All 13 photo URLs verified HTTP 200. The `_preview.html` files were a brief detour and have been deleted — they are NOT the site (see Key Learnings). `main` is canonical — pull from it at session start.
GitHub repo **`avilaivan42-cyber/Meza-General-Contractors-`** (branch **`main`**) is the single source of truth for all live HTML. The 5 production pages there are current: index.html, about.html, commercial.html, contact.html, insurance-claims.html.
- Claude's bash environment **CAN fetch directly** (raw.githubusercontent.com / git clone) — no need to upload files each session. Pull from `main` at session start.
- raw `main` URL can serve a stale CDN copy for a few minutes; for authoritative checks use the commit SHA or the API. (GitHub **API** can rate-limit unauthenticated; raw fetches are the reliable fallback.)
- Claude **cannot push** to the repo (no write credentials) — commits are Ivan's.
- **projects.html DELETED** from repo (confirmed at commit 9fe89ea). Page was cancelled — do not recreate. Real job photos now live INSIDE the money pages (Session 9), which was always the plan.
- **(Session 9) Project photos live at repo ROOT** (13 `*.webp`, alongside `logo.png`) and are referenced by **full raw GitHub URLs** (`https://raw.githubusercontent.com/avilaivan42-cyber/Meza-General-Contractors-/main/<name>.webp`) — same pattern the logo already uses. **No `images/projects/` subfolder** (the relative-folder plan was dropped to remove the upload-the-folder friction). Terry portrait is base64 in about.html + index family section.
- Loose unreferenced source assets in repo root (WhatsApp images/videos from the May 12 residential + May 13 commercial jobs, terry-meza*.jpg) are raw originals. Hostinger deploys the repo folder.

---

## OPERATOR ROLE

Senior consultant + operator for Meza. Decisive, concise, no fluff. Make calls when delegated. Push back on strategic errors.

**Decision Authority:**
- ✅ Decide: content, design, tools, copy, workflows
- 🔒 Approval needed: spend >$50, vendor contracts, pricing, legal claims, strategic pivots

**Never:** fake reviews, deceptive marketing, unethical REO tactics (notice interception, shadow evictions), claims of licenses/insurance without confirmed details, assumptions about Spanish-speaking customers. Never claim to "file claims on behalf of" homeowners — public adjuster language. Always frame as "help document" or "help support the claims process."

**Communication:** "Do this" not "you might consider." User time is the scarcest resource.

---

## BUSINESS CORE

| Field | Detail |
|-------|--------|
| Business | Meza General Contractors |
| Founded | 1958 (68 years) |
| Owner — Field/Sales | Terry Meza Sr. (Houston) — second generation |
| Operations/Admin | Miriam "Mia" Meza (Houston) |
| Remote Director | Ivan (Cuernavaca, Mexico) |
| Phone | (346) 281-4358 |
| Address | PO Box — do NOT display street address on website. Use "Houston, TX — Serving a 100-Mile Radius" |
| Domain | mezageneralcontractors.com (secured, on Hostinger) |
| Service Area | 100-mile radius from Houston |
| Languages | English + Spanish (competitive advantage) |
| Email | info@mezageneralcontractors.com / claims@mezageneralcontractors.com (Hostinger — NOT Google Workspace) |

**Two Businesses:**
- **B2C Roofing & Insurance Claims** — ACTIVE, growth phase
- **B2B REO Property Services** — DORMANT, restart pending

---

## ACTIVE: ROOFING & INSURANCE CLAIMS (B2C)

**Hero Message (insurance-claims.html):** "68 years of storm-damage expertise on your side." + red sub-line "Free for Houston property owners." (Session 7 — replaced "Decades of Storm Damage Expertise"; "Decades" retired from hero per specificity rule)
**Spanish (current approved version — Mia):** "¡También hablamos español! En Meza General Contractors no solo reparamos techos; blindamos la tranquilidad de su hogar. Desde un diagnóstico físico de daños preciso y sin costo, hasta la reconstrucción total de su propiedad, le acompañamos paso a paso en español. No deje su patrimonio al azar; confíe en el sello de protección Meza que cuida a Houston desde 1958."
**Note:** ChatGPT flagged this copy as too dramatic. Held for Mia review before any changes.

**85% STAT — ELIMINATED.** Do not use it anywhere, ever. Removed from all pages.

**Differentiator:** Document BEFORE homeowner contacts insurer. Documentation-first methodology.

**Legal guardrails — ALWAYS:**
- Never say "we file claims on your behalf" → say "we help you document" or "we help support the claims process"
- Never say "NOAA proves" → say "NOAA establishes the timeline"
- Never promise supplements or second looks — conditioned on policy
- Do NOT use 85% stat — eliminated
- Denied claims → "access to independent attorneys" not "we fight for you"
- Never use absolute claims like "ensuring nothing gets minimized or missed"
- Frame as "documentation-first" not "claim-first"
- $950 damage-assessment data package — INTERNAL pricing only; the "waived" inducement was REMOVED from insurance-claims site copy (Session 8, regulator-risk). Do not re-add to the site.

**Revenue Lines:**
| Line | Margin/Job | Status |
|------|------------|--------|
| Insurance claims (PRIMARY) | $5K–$8K+ | High potential, marketing-led |
| Cash/no-insurance | $1K–$2K | Saturated, secondary |

**Services:** Roofing (residential + commercial), initial evaluation + claim documentation support, seamless gutters, interior/exterior painting, denied-claim independent attorney referral, flexible financing for qualifying homeowners.

**North Star:** 10 inspections → 3-5 insurance jobs → $15K–$40K from $500 ad spend.
**Current volume:** 2-3 jobs/month (word of mouth). **Target:** 15-20/month by end of Month 2.

---

## TEAM LANES (no overlap)

**Ivan (Remote Director):** All digital infrastructure ownership, paid ads, lead routing, content/copy, KPI tracking, vendor relationships, strategic decisions.

**Terry (Field):** Free damage assessments (same/next day), close deals, oversee crews, supply raw content (photos + 30-sec voice notes per job), community events 2x/week. Note: Terry does NOT personally do rooftop inspections anymore — crew handles that.

**Mia (Operations):** Phone/WhatsApp backup, calendar Terry's assessments, coordinate active jobs, payment collection, 48-hr customer follow-up, Google review requests. Content reviewer — all copy must pass Mia before publishing.

**RULE:** Every account Mia creates → credentials to Ivan IMMEDIATELY before any other action.

---

## WEBSITE STATUS

### ✅ DONE — LOCKED (do not modify without explicit instruction)
- **about.html** — Terry photo embedded (base64). Projects link removed from footer. top-wa/float-call var(--blue). Session 8 trust bar + SVG icons + white/light-blue rhythm canonical. **Session 9: UNCHANGED (byte-for-byte from main).** Stable — modify only on explicit instruction.
- **contact.html** — complete pending Formspree ID. Spanish section removed (English-only decision). `YOUR_FORM_ID` placeholder expected. top-wa/float-call var(--blue). **Session 9: UNCHANGED (byte-for-byte from main).**
- **commercial.html** — complete. 68+ → 68 fixed. **Session 9: real Before→After photo showcase added (see Session 9 block).** float-call var(--blue).
- **insurance-claims.html** — **Session 9: real residential documentation gallery added to Real Results (see Session 9 block).** All rules clean. float-call var(--blue).
- **index.html** — Session 4 overhaul, Session 6 updates. **Session 9: real photos added to both project cards.**

### ✅ SESSION 7 — COMPLETE (May 29, 2026)
(Sitewide "Damage Assessment" → "Free Initial Evaluation" sweep; insurance/about/contact/index/commercial copy fixes; projects.html deleted; Terry photo re-optimized + base64. Verified by grep, md5-confirmed on `main`.)

### ✅ SESSION 8 — COMPLETE (May 30, 2026) — committed `1d30512`, verified byte-for-byte
- Credential trust bar sitewide; emoji→inline SVG icons (0 decorative emoji); white↔light-blue section rhythm (grey retired for SECTIONS); commercial nav CTA → "Request a Consultation"; fixed stray `</div>` in insurance Important Notice.
- Contact form BUILT (`id="contact-form"` → Formspree `YOUR_FORM_ID`, `_gotcha` honeypot) — inert until real ID + 1 test.
- GA4 + conversion events on all 5 (placeholder `G-XXXXXXXXXX` 2×/page) — no data until real ID + key events marked.
- Google review strips (index full + insurance/contact compact) — all placeholders, hide until ~5 real reviews.
- index testimonials (Robert G., Shonda W., James R.) confirmed genuine verbatim — keep word-for-word.

### ✅ SESSION 9 — COMPLETE + COMMITTED (June 1, 2026) — on `main`, commit `f227ff0`, verified
**Goal:** close the "Real visual proof" gap (was a C — thinnest spot on the site). Used real repo media from two May 2026 jobs (residential, May 12 / commercial, May 13). Screened clean: no faces, no readable addresses/plates, no claim paperwork. **Photo consent CONFIRMED by Mia/Terry for both properties** (June 1) — the "shown with property-owner permission" captions are accurate.

- **Decision: did NOT revive projects.html.** Embedded the proof into the money pages instead, split by editorial fit. (projects.html stays cancelled.)
- **13 optimized WebP committed at repo ROOT** (alongside logo.png), referenced by **full raw GitHub URLs** (matches the logo pattern — no `images/projects/` subfolder; the relative-folder plan was dropped after it caused repeated "forgot the folder" friction). Filenames: `commercial-before/after/crane/tearoff/detail`, `residential-flashing/decking/boot/field/flashing-line/repair`, `card-commercial`, `card-residential`. ~1.4MB total, all ≤~255KB (target ~150KB).
- **commercial.html** — real **Before→After showcase** inside "Featured Projects" (old patched flat roof → new white TPO), + crane/tear-off/detail thumbnails. The two existing descriptive cards (Multi-Family, Warehouse) left intact below — NOT relabeled with this job's photos (honesty).
- **insurance-claims.html** — real **"From Documentation to Repair" gallery** inside Real Results (after the 3 Homeowner's-Voice case cards): residential field/boots/decking/flashing = the documentation-first story. Section title stays "Recent Storm Damage Projects" — only the residential storm job lives here (commercial job belongs on commercial.html, hence the split).
- **index.html** — real photo on BOTH project cards (`.proj-photo`, 200px object-fit cover). Residential card = new flashing shot; commercial card = white TPO after.
- **Shared lightbox** — `pj-` prefixed CSS + one delegated JS (builds image arrays from each `.pj-gallery` in DOM order; ESC/arrow-key/click-out close). On commercial.html + insurance-claims.html. index cards are plain photos (no lightbox).
- **No ImageObject schema added** — per rule #4 (standard SEO = AI SEO); descriptive alt text on every photo is the lever instead.
- **Verified live (June 1):** all 13 raw photo URLs return HTTP 200; per-page photo refs = index 2 / commercial 5 / insurance 6 / about 0 / contact 0; nav links intact on all 5; 0 `_preview` refs; all 5 tag-balanced; 0 banned terms; 0 `projects.html` links.
- **CTA wording decision (reaffirmed):** kept **"Free Initial Evaluation"** sitewide. A one-off session rule proposing "Get Immediate Support" was raised and REJECTED — locked standard wins.

### ❌ CANCELLED
- **projects.html** — no dedicated projects page. **Session 9 fulfilled the underlying need**: real before/after + documentation photos now embedded in index cards, insurance-claims Real Results, and commercial Featured Projects.

### 🔄 IN PROGRESS (Mia)
- Facebook Business Page / Instagram Business / WhatsApp Business install / TikTok Business

### 🔴 BLOCKING LAUNCH
- [x] **Commit Session 9 to `main`** — DONE June 1, commit `f227ff0` (5 pages + 13 root WebP), verified (13 photo URLs HTTP 200, nav intact, 0 `_preview` refs).
- [ ] **Confirm site is LIVE on Hostinger** — repo is correct, but the public domain only reflects it IF Hostinger pulls from the repo. **OPEN: does `mezageneralcontractors.com` auto-serve from the GitHub repo, or need a manual `/public_html` upload?** Resolve, then load the live URL and click through every menu link + check photos.
- [ ] **Formspree form ID** — replace `YOUR_FORM_ID` in contact.html + one real test submission.
- [ ] **GA4 Measurement ID** — replace `G-XXXXXXXXXX` (2×/page, all 5) + mark key events: generate_lead, contact_call, contact_text, contact_whatsapp.
- [ ] **Google rating values** — populate `[4.9]`, `[40]+`, `[YOUR_GOOGLE_REVIEWS_URL]`; hide strips until ~5 real reviews.
- [ ] **TX contractor license #** — still a `[LICENSE]` placeholder.
- [ ] **Mia sign-off** — insurance-claims legal/case-card copy before publish.
- [x] **Photo consent** (both Session 9 jobs) — CONFIRMED June 1 (Mia/Terry).

### ⏳ POST-LAUNCH — WEEK 1 (priority order)
- [ ] Google Business Profile — set up under info@ — DAY 1, not optional
- [ ] Google Maps embed on contact page
- [ ] Facebook ad — insurance claims video — $250
- [ ] WhatsApp blast to 50+ past customers
- [ ] Google review collection workflow
- [ ] Terry 90-sec Spanish intro video (smartphone)

### ⏳ POST-LAUNCH — GROWTH
- [x] **Real before/after job photos** — DONE Session 9 (index cards + insurance Real Results + commercial Before→After), pending commit/deploy.
- [ ] More real photos as available: Mia, trucks, additional completed jobs, team/family — add to insurance Real Results + commercial. Optimize via squoosh.app → ~150KB WebP (or reuse the Session 9 PIL pipeline: longest side ~1200–1400px, WebP q60–80) before upload.
- [ ] Add the May-2026 job VIDEOS (1 residential, 8 commercial in repo root) where useful — short clips boost AI surface visibility.
- [ ] Facebook/Instagram/TikTok Business — complete setup
- [ ] Paid ads — scale after proof of concept

### 📋 KNOWN OPEN ISSUES
- **Live-site status unconfirmed** — repo `main` is correct + verified (commit `f227ff0`), but whether `mezageneralcontractors.com` reflects it depends on the Hostinger serving mechanism (open question). Load the live URL to confirm.
- contact.html `YOUR_FORM_ID` — built, non-functional until real Formspree endpoint + 1 test.
- GA4 `G-XXXXXXXXXX` placeholder (2×/page, all 5) — no data until real ID + key events marked.
- Google review strips placeholders — populate from real GBP; hide until ~5 reviews.
- `[LICENSE]` placeholder — TX contractor license number still needed.
- Links/images in Claude preview don't navigate/render — normal. Test in browser (or use the embedded-image `*_preview.html` copies).

---

## KEY LEARNINGS
- **Preview files are viewing-only — never ship them as the site.** Session 9 detour: the base64-embedded `*_preview.html` copies were briefly committed (and the real pages deleted). That breaks a live site three ways: (1) no `index.html` = no homepage; (2) nav/footer link to `index.html`/`about.html`/etc., so `*_preview.html` names 404 every menu click; (3) base64 photos have no image URL, killing image/AI indexability (against rule #2). **One canonical, correctly-named version of each page lives in the repo. Previews stay out of the repo.**
- **Claude reads whatever is in the repo at fetch time** — Ivan does NOT need to curate/delete versions "so Claude won't get confused." Keep the repo as the clean source of truth for the *site*, not for Claude's benefit.
- **Image hosting (resolved):** project photos = real `*.webp` files at repo ROOT via raw GitHub URLs (matches the existing logo pattern). Chosen over (a) a relative `images/projects/` subfolder — kept getting forgotten on upload/deploy — and (b) base64 — kills indexability + bloats pages. Raw URLs render the instant the files are in the repo, with no folder to manage.
- **Verify deploys, don't assume:** after a push, fetch the raw HTML + HEAD/GET the image URLs (expect HTTP 200) and confirm nav links + 0 `_preview` refs. Repo-correct ≠ live-correct until the Hostinger serving path is confirmed.

---

## AUDIT PROTOCOL
**Always audit from inside this project folder.**

**Audit checklist for all HTML files:**
- No `68+` or `65+` — always `68 years` or `68`
- No `[LICENSE]` placeholder (still expected until license # confirmed)
- Float WhatsApp button → `https://wa.me/13462814358`
- `top-wa` background → `var(--blue)`; `top-wa:hover` → `#152d6b`
- **NO 85% stat anywhere**
- **NO "Damage Assessment" anywhere** — verify 0 instances
- Article guard: "an initial evaluation," never "a initial evaluation"
- No footer link to projects.html — page cancelled
- Nav CTA: "Free Initial Evaluation" — except commercial: "Request a Consultation"
- Terry photo base64 present in about.html
- No black backgrounds; no third-party fonts (Oswald + Lato only); no hardcoded `#1E3A8A` (use `var(--blue)`, gradient exception only)
- `:root{--blue:#1E3A8A}` definition is correct — do not change
- (Session 8) 0 decorative emoji sitewide; only allowed glyph is review star `&#9733;` (gold `#fbbf24`)
- (Session 8) Credential trust bar on all 5 pages under the hero
- (Session 8) Section backgrounds = white ↔ `var(--blue-lt)` only — 0 grey SECTION backgrounds (cards/boxes may use grey)
- (Session 8) contact.html has real `<form id="contact-form">` → `YOUR_FORM_ID`; `_gotcha` present
- (Session 8) GA4 on all 5 — `G-XXXXXXXXXX` (2×/page) + delegated events
- (Session 8) Tag balance — every page balanced `<div>`/`</div>` and `<section>`/`</section>`
- **(Session 9) All 13 project `*.webp` live at repo ROOT** and are referenced by full raw GitHub URLs (matches logo). Verify each URL returns HTTP 200 (raw CDN may lag a few min after a push). No `images/projects/` subfolder; no base64-embedded project photos in production.
- **(Session 9) `pj-` lightbox** present on commercial + insurance (one `#pjlb` per page, one delegated script); index cards are plain `.proj-photo` images (no lightbox)
- **(Session 9) Consent captions** ("shown with property-owner permission") on commercial + insurance galleries — accurate as of June 1 confirmation
- **(Session 9) projects.html still absent**; real photos embedded in money pages only

---

## DESIGN SYSTEM (website)
- Red `#C41E1E` / Blue `#1E3A8A` / hover blue `#152d6b` / light blue `var(--blue-lt)` = `#eef2fb`
- Fonts: Oswald (headings) + Lato (body) — Lato weights: 400, 700, 900
- Mobile-first, hamburger menu at 960px
- Logo: `logo.png` (repo root)
- Year references: always "68 years" — never "65+" or "68+"
- Section padding: `48px 0` on insurance-claims.html — `72px 0` on all other pages
- Section alternating (Session 8): **white (`#fff`) ↔ light blue (`var(--blue-lt)`).** Grey retired for SECTION backgrounds; still used for cards/boxes.
- Content max-width: `.wrap` = 1160px; constrained sections = 860px–980px centered
- Terry photo: base64 embedded in about.html (and index family section) — always include, never remove
- **No black backgrounds. No glassmorphism. Bootstrap rejected.** Audience = everyday Houston homeowners, not VC/SaaS.
- **Hero eyebrow on index.html: blue pill — intentional, do not change to red**
- **(Session 9) Project imagery:** real photos as `*.webp` at repo ROOT, referenced by full raw GitHub URLs (same as logo.png), optimized to ~150KB (≤~255KB), longest side ~1200–1400px. Galleries use `pj-` prefixed classes + a shared delegated lightbox. Commercial uses a labeled **Before (red tag) / After (blue tag)** device; insurance uses a documentation-first lead+thumbnail layout. Descriptive alt text on every image (AI-SEO lever; no ImageObject schema needed). **Production never ships base64-embedded project photos** (kills image indexability) — those were viewing-only previews.

---

## COPY STANDARDS
- "Free Initial Evaluation" — always this phrase (REPLACED "Free Damage Assessment" sitewide, Session 7). Never "inspection." "Damage Assessment" RETIRED — 0 instances allowed. **(Session 9) "Get Immediate Support" alternative considered and REJECTED — "Free Initial Evaluation" is the locked nav/CTA standard.**
- "Initial Evaluation" — capitalized. Article: "an initial evaluation," never "a initial evaluation."
- "Homeowner's Responsibility Share" — not "deductible"
- "68 years" — not "68+" or "65+"
- Urgency line: "Every Day You Wait, the Damage Grows."
- Legal section title on contact: "Our Commitment" — never "Assessment Guarantees"
- claims@mezageneralcontractors.com appears in footer Contact section of all pages
- Harvey quote attribution: Terry Meza Sr., Owner & Field Director (NOT Founder)
- "Documentation-first" — not "claim-first"
- No absolute claims: never "ensuring nothing gets minimized or missed"
- Nav CTA: "Free Initial Evaluation" on all pages except commercial ("Request a Consultation")
- Top bar "Text Us" button: blue `var(--blue)`, links to `sms:3462814358`
- Float WhatsApp button: green `#25D366`, links to `https://wa.me/13462814358`; hover `#152d6b` (never WhatsApp green)
- "Multi-generational" — confirmed accurate (Terry is second generation)
- CTA buttons: "Talk to Us →" (not "Talk to Terry →")
- **Never use 85% stat — eliminated**
- Important Notice text: always center-justified
- **Website language: English only.** Spanish-language form/page copy prohibited. Bilingual-service references ("También hablamos español", "English & Español") are English statements about service — they stay.
- "paying out-of-pocket" / "Texas-tough roof replacement" / "true Texas transparency" — index.html hero solution box phrases, locked
- Hero CTAs on index: "Schedule Your Free Initial Evaluation" / "(346) 281-4358"
- **(Session 9) Photo captions:** "Real Meza job ... shown with property-owner permission." — approved/accurate (consent confirmed June 1).

---

## BUDGET
- **Proof-of-concept ad budget:** $500 total
- **Hostinger hosting:** included (Mia has credentials)
- **Email:** Hostinger (included) — info@ and claims@
- No other spend without approval

---

## DORMANT: REO PROPERTY SERVICES (B2B)

Property preservation, inspection, and compliance services for banks/lenders on foreclosed Texas properties. Restart pending after B2C stabilizes.

**Off-limits tactics:** notice interception, shadow evictions, any maneuver labeled "unethical" or "gray."

---

## OPEN QUESTIONS
1. TX contractor license number (for [LICENSE] placeholder) — pending.
2. Hostinger native form handling (hPanel) vs Formspree — confirm before launch; drop endpoint into contact.html `YOUR_FORM_ID`.
3. **(Session 9) Hostinger deploy mechanism** — does `mezageneralcontractors.com` auto-serve from the GitHub repo, or need a manual `/public_html` upload? Repo is correct; this is the only thing between the repo and a confirmed-live site. (Project photos load from raw GitHub URLs regardless, so no image folder to ship.)
4. Spanish copy reconciliation — production files are English-only (only "Español" service references remain). Mia to confirm: re-add a Spanish service paragraph or keep English-only. (Flagged Session 7.)
