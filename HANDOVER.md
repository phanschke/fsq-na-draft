# HANDOVER — FSQ NA website (`C:\engineering\fsq-na-deploy`)

Written 2026-07-22. Read this first, then `git log` and the four HTML pages.

## What this repo is
Static HTML draft of the **FSQ Experts North America** website.
- Pages: `index.html`, `about.html`, `services.html`, `industries.html` + `assets/`.
- GitHub: `origin` = https://github.com/phanschke/fsq-na-draft.git, branch `master`.
- Every page is `noindex, nofollow` and carries a visible DRAFT review legend.
- Content is tagged with two review chips (VERIFIED[source: index.html:14-19, about.html:14-18]):
  - **`ORIGINAL`** — copy from fsq-experts.com (the German site); FSQ holds the copyright.
  - **`NA · NEW`** — proposed additions from the NA market strategy (regulation clocks,
    Canadian market data, NA regulatory packages, structural-independence copy, etc.),
    much of it still marked unverified / pending confirmation.

## The goal (Peter, 2026-07-22)
Two parallel versions of the site:

1. **Current version — KEEP AS-IS.** The full evolved draft that mixes `ORIGINAL` +
   `NA · NEW` content. Do not gut it; it stays the working "everything" draft.

2. **NEW go-live-minimal version — TO BUILD.** A pared-back site that ships FIRST, using
   **only original FSQ Germany content** (the `ORIGINAL`-tagged copy), so we can go live
   quickly on defensible, copyright-owned material and then **slowly add the NA content
   back on** piece by piece.
   - **Strip:** the `NA · NEW` market-strategy sections (regulation clock, Canadian market
     figures, NA regulatory packages, "why independence is structural," success-story NA
     framing, unverified stats, the DRAFT review legend/tags themselves).
   - **KEEP the local references** — the NA localization is retained: FSQ NA branding/logos,
     the Toronto HQ / locations line, English copy, and the NA contact details/mailboxes.
     ("Original German content only" refers to the *marketing/strategy body copy*, not to
     reverting the localization.)
   - This version **also needs its own GitHub access** (its own repo or branch — decide below).

## Open decisions (resolve at start of the build session)
1. **How to separate the two versions on GitHub** — options:
   - (a) new branch `go-live-min` in this same repo (simplest, one repo, GitHub Pages per branch), or
   - (b) a second repo (e.g. `fsq-na-live`) for a clean public/go-live surface.
   Recommend (a) first — a branch — unless Peter wants a separate public repo.
2. **Exact keep/strip line per page** — walk each of the 4 pages, rule each section
   ORIGINAL-keep vs NA-strip, before editing. The audit is the product: read each section's
   own tag, don't infer from memory.
3. Whether the go-live version drops `noindex` + the DRAFT legend (it should, to actually go live).

## Do NOT
- Do not `.Send()` anything; this is website work, not email.
- Do not delete or overwrite the current mixed draft — the minimal version is additive/parallel.
- Do not treat any `NA · NEW` figure as verified — most are tagged unverified in-page.

## Status
Goal captured only. No build work started yet. Next session: resolve the 3 open decisions
(recommend branch + per-page audit), then create the minimal version.
