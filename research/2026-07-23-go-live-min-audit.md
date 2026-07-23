# Go-live-minimal audit — FSQ NA website

Date: 2026-07-23. Branch built from this audit: `go-live-min` (off `master`).
Decisions (Peter, 2026-07-23): (1) separate via **new branch `go-live-min`**, one repo;
(2) **keep `noindex,nofollow`** + a lighter draft marker until Peter approves — do NOT go
public yet; (3) per-page keep/strip audit below (Claude's call, per handover).

## Rule set
Source of truth = each section's own in-page review tag (VERIFIED[source: the 4 HTML pages,
`.tag t-orig` / `.tag t-new` / `.na-card` / `.new-na` / `.new-inline` / `.c-new` / `.legend`
/ `.foot-note` markers]).

- **KEEP** = `ORIGINAL`-tagged copy (© Wertefest GmbH / FSQ Experts, from fsq-experts.com) —
  preserved **byte-for-byte** (copyright-owned; do not paraphrase).
- **KEEP (localization)** = NA branding/logos, Toronto HQ + `Toronto · New York · Munich ·
  Berlin-Schoenefeld` locations line, English copy, NA team roster + `@fsqexpertsna.com`
  mailboxes/LinkedIn, the Toronto office address. (Handover: "original German content only"
  = the marketing/strategy body copy, NOT the localization.)
- **STRIP** = `NA · NEW` market-strategy body copy + the review instrument itself.

## Global (all 4 pages)
| Element | Ruling |
|---|---|
| `<meta robots noindex,nofollow>` (line 5) | **KEEP** (decision 2 — not going public yet) |
| `.legend` DRAFT review-key block (14-19) | **STRIP** → replace with one-line lighter draft marker |
| Header nav + `logo-wide.png` brand | **KEEP** (localization) |
| Footer logo, `Toronto · New York · Munich · Berlin-Schoenefeld`, LinkedIn, fsq-experts.com link | **KEEP** (localization) |
| Footer `.foot-note` INTERNAL DRAFT block | **STRIP** → replace with short © line |
| All `.tag t-orig` / `.tag t-new` review chips | **STRIP** (review instrument) |
| `.new-inline` chips (green, inside orig chip rows) | **STRIP** (NA additions) |
| `.c-new` chips (green, in standards wall) | **STRIP** (NA additions) |
| `.na-card` cards / `.new-na` blocks | **STRIP** (NA·NEW body copy) |

## index.html
- **Hero (37-66)** — HYBRID. `.new-na` block (40-50) STRIP the NA-strategy claims ("global
  engineering bench with regulatory delivery before Health Canada, the FDA…"), but the
  Toronto/locations **kicker is localization → KEEP**. Headline "Canada's independent partner
  for safety-critical products" is NA positioning → replaced with an **ORIGINAL-derived**
  headline drawn from the original lede vocabulary ("specialized expertise…safety and
  cybersecurity"), since the repo holds no verbatim original H1. ORIGINAL lede (51-60) KEEP.
  Buttons: reword "Explore NA services" → "Explore our services" (NA-packages target stripped).
- **Challenges band (68-100)** — ORIGINAL left col KEEP; `.new-na` "the rules just changed"
  (82-98) STRIP; drop `two-col` → single column.
- **Solutions (102-151)** — 5 ORIGINAL cards KEEP; 6th `.na-card` "North America Regulatory
  Packages" (138-148) STRIP.
- **Industries teaser (153-195)** — ORIGINAL cards KEEP; strip 6 `.new-inline` chips.
- **Success stories (197-236)** — 3 ORIGINAL cards KEEP; `.na-card` "Why this matters for
  Canadian manufacturers" (226-233) STRIP.
- **CTA (238-247)** KEEP. Footer per global.

## about.html
- **Hero (35-46)** — all ORIGINAL, KEEP.
- **Facts (48-79)** — ORIGINAL stats KEEP; locations line (57, wrapped `.new-inline`) is
  localization → KEEP text, unwrap the green styling. `.new-na` "Why our independence is
  structural" (62-77) STRIP; drop `two-col`.
- **Canadian market context (81-118)** — entire `.new-na` section (unverified StatCan / ISED /
  Toronto Global / Alstom figures) STRIP (explicit strip-list item).
- **Values (120-133)** — all ORIGINAL KEEP.
- **Team (135-169)** — ORIGINAL heading + lede KEEP; `.new-na` "Visible experts, by policy"
  (146-152) + mailbox draft-note (153-156) STRIP; **team roster (157-165) KEEP** (localization:
  NA contact details/mailboxes — acceptable in a noindex draft even though mailboxes are not yet
  provisioned).
- **Contact (171-187)** — ORIGINAL heading KEEP; from the `.new-na` block keep only the
  localization address "FSQ Experts NA Inc. · Toronto, Ontario", strip "Serving the US from
  Canada under USMCA" (strategy) + "to be confirmed" (draft note); unwrap green styling.
  mailto CTA KEEP.

## services.html
- **Hero (35-45)** — kicker KEEP; h1 "…and what's new for North America" → strip NA framing to
  "Our solutions & services"; ORIGINAL lede KEEP.
- **Regulation clock (47-94)** — STRIP entire section (explicit strip-list item).
- **NA packages (96-248)** — STRIP entire `#na-packages` section (11 `.na-card` offers).
- **Five ORIGINAL solution fields (250-367)** — KEEP; strip the two `.new-na` "NA angle"
  callouts (market-access 291-297, product-safety 337-343).
- **Standards wall (369-463)** — KEEP neutral `.chip`; strip all `.c-new` chips; strip both
  chip-explainer ledes (374-378) and the `.new-na` publication-gate note (457-461); retitle
  "…old and new" → "The standards we work in".
- **Products (466-505)** — 3 ORIGINAL cards KEEP; strip the `.new-na` callout inside "AI
  Driver's License" (486-491).
- CTA + footer per global.

## industries.html
- **Hero (35-61)** — ORIGINAL kicker/h1/lede KEEP; `.new-na` chip-system explainer (43-51)
  STRIP; sub-nav KEEP.
- **6 industry articles (medical, automotive, railway, aerospace, defense, machinery)** — each:
  ORIGINAL intro + `.orig` "What we deliver today" fact-list + neutral chips KEEP; the `.new-na`
  "What FSQ NA adds" half STRIP; drop `split` → full width.
- **Emerging & Adjacent Domains (395-436)** — STRIP entire `.new-na` article.
- CTA + footer per global. (Sub-nav has no `#emerging` link → no broken anchor.)

## Broken-anchor check
All stripped anchors (`#reg-clock`, `#na-packages`) are only linked **from within** stripped
`.new-na`/`.na-card` blocks → removed together, no dangling links. ORIGINAL cross-links
(`#efficient-compliance`, `#medical`, etc.) target KEPT sections. VERIFIED[source: grep of
`href="services.html#` and `href="industries.html#` across the 4 pages].

## Not touched
`assets/style.css` — leftover `.na-card`/`.new-na`/`.reg-clock`/`.c-new`/`.new-inline` rules
are harmless when unused; `.legend`/`.foot-note` reused for the lighter markers. No CSS edits.
