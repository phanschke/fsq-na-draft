# US + Canada regulatory horizon — the gap the EU-heavy scan missed

Scanned 2026-07-24 (parallel agents, primary US/Canada gov sources). This complements
`2026-07-24-standards-horizon-scan.md` (which was ~26 EU vs 3 US / 5 Canada mentions).

**Direct answer to "does this apply to US & Canada?"**
- The **standard revisions** (IEC 62304 Ed 2, ISO 12100 Ed 2, DO-326B, ISO 10218:2025, etc.) are
  **jurisdiction-neutral** — a Toronto or US manufacturer uses the same ISO/IEC/RTCA documents, so
  those changes hit them too. What differs is *which regulator mandates which standard*.
- The **regulatory drivers** are very different by country, and the NA side is **highly active** —
  arguably more relevant to FSQ NA's home + export markets than the EU items. Details below.

---

## 🇺🇸 UNITED STATES

### Medical (FDA)
- **QMSR (21 CFR 820)** — **in force since 2 Feb 2026**; ISO 13485:2016 incorporated by reference; FDA moved to Compliance Program 7382.850. Plus **technical-amendments final rule (Dec 2025)** and a **draft guidance on QMS info in premarket submissions (Nov 2025)**. → drives ISO 13485 / IEC 62304 evidence. **CHANGING SOON.**
- **§524B cybersecurity final guidance (27 Jun 2025)** — finalized; "cyber device" premarket content. **STABLE (recent).**
- **§515C PCCP final guidance (Dec 2024)** — AI-enabled device pre-authorized changes. **STABLE.**
- **AI-Enabled Device Software Functions — Lifecycle Management draft guidance (Jan 2025)** — comment closed Apr 2025; **CDRH FY2026 final-guidance target**. → IEC 62304, AI/ML SaMD. **CHANGING SOON.**

### Aerospace (FAA)
- **§25.1319 aircraft cyber NPRM (RIN 2120-AL94, Aug 2024)** — still **proposed**; comments closed Oct 2024; companion draft AC ("AC 20-XXX") in the docket; no final rule/effective date yet. → DO-326/356/355 family becomes mandatory AMC. **WATCH.**
- **FAA AI/ML certification** — roadmap/policy stage only, no rule. **WATCH.**

### Automotive (NHTSA)
- **AV Framework — 3 FMVSS modernization rulemakings** (announced Sept 2025; FMVSS 102/103/104/108) to let ADS vehicles without manual controls comply; Part 555 exemption streamlining (up to 2,500/yr). → ANSI/UL 4600, ISO/PAS 8800 safety-case work. **CHANGING SOON.**
- **AV STEP voluntary reporting program — WITHDRAWN (26 Jun 2026).** **STABLE (settled).**
- **NHTSA vehicle cyber best practices** — 2022 edition, no replacement pending. **STABLE.**

### Product cybersecurity (NIST / DoD / CISA)
- **CMMC — Phase II SUSPENDED (immediate, ~mid-July 2026)** by the Department of War (memo **26-P-1023**). Phase II (Level 2 **C3PAO** for CUI + Level 3) had been scheduled for **10 Nov 2026**; during the suspension only **Level 1 (Self)** and **Level 2 (Self)** apply, and contracting officers must remove higher CMMC levels from solicitations and existing contracts. The 32 CFR 170 program rule and DFARS remain, but the Phase II gate is **paused pending review**. → NIST SP 800-171/172. **WATCH (paused).**
  ✅ **CONFLICT RESOLVED (2026-07-24):** the 2026-07-23 note ("Phase II suspended") was CORRECT; this scan's earlier "no suspension / Phase 2 from Nov 2026" was WRONG (it relied on a pre-suspension secondary source, Baker Tilly). Confirmed via DoD **primary domains** business.defense.gov + dodcio.defense.gov (memo 26-P-1023) — capture: scratchpad/cmmc-status-primary-source.txt. Exact memo **day** UNKNOWN (verbatim PDF Akamai-blocked to all fetchers; "~mid-July 2026 / 13 Jul" per the DoD pages).
- **NIST SP 800-171 Rev 3 (May 2024)** final, but CMMC still contractually references **Rev 2** — Rev 3 adoption pending. **WATCH.**
- **CISA 2025 SBOM Minimum Elements** — draft, comment closed Oct 2025, final revision pending. **CHANGING SOON.**
- **NIST CSF 2.0** — current, no successor. **STABLE.**

### AI governance (US federal)
- **EO 14179 (Jan 2025)** deregulatory + **America's AI Action Plan (Jul 2025)** directing a **NIST AI RMF revision**; **EO 14365 (Dec 2025)** federal AI framework / state-law preemption; **NIST Cyber AI Profile (NISTIR 8596) draft (Dec 2025)**. NIST **AI RMF 1.0** still current. → ISO/IEC 42001/23894 backdrop; US stays voluntary/pro-innovation. **CHANGING SOON (policy).**

### Machinery (OSHA)
- **No federal robotics rule**; regulated via General Duty Clause + 29 CFR 1910 Subpart O + consensus standards (ANSI/RIA R15.06 = ISO 10218; RIA TR R15.606 = ISO/TS 15066). The **ISO 10218:2025** revision drives future US adoption, not an OSHA rule. **STABLE (OSHA).**

---

## 🇨🇦 CANADA

### Medical (Health Canada)
- **MLMD guidance + PCCP finalized (Feb 2025)** — new operational mechanism for ML-enabled devices. → IEC 62304, ISO 14971, AI/ML. **CHANGING SOON.**
- **SOR/2024-238** — expanded terms & conditions, recalls, post-market oversight; key MDR sections **in force 1 Jan 2026**. **CHANGING SOON.**
- **SOR/2026-110** — MDEL (establishment licence) modernization; in force **~Dec 2026**. **CHANGING SOON.**
- **Pre-market device cybersecurity guidance** — 2019 (rec. modified 2023), no pending change. **STABLE.**
- IEC 60601 series: no Canada-specific pending regulatory item found. UNKNOWN.

### AI governance (Canada)
- **AIDA (Bill C-27 Part 3) — DIED** at prorogation of the 44th Parliament; no successor bill before Parliament now. → the **Voluntary Code of Conduct on Advanced Generative AI (ISED, Sept 2023)** is the operative instrument. Maps to ISO/IEC 42001/23894. **WATCH** (regulatory vacuum; concepts likely to return).

### Automotive / Transport (Transport Canada)
- **Vehicle cyber regime stays VOLUNTARY** — TC Vehicle Cyber Security Strategy + **VCAT** self-assessment; **no move to mandate UN R155/R156**; ISO/SAE 21434 tracked as baseline. **STABLE.**
- **AV safety assessment** — voluntary guidance, self-certification. **STABLE.** (So Canadian clients' *real* cyber clock is their export market's, per FSQ's own positioning.)

### Critical cyber / Rail (CCSPA)
- **CCSPA (Bill C-8) — RECEIVED ROYAL ASSENT ~15/16 Jun 2026** (now law). Telecom amendments in force immediately; **CCSPA Part 2 comes into force by Governor-in-Council order; designation + reporting regs still to come** (report window ≤72h; cyber program ≤90 days of designation). **Transportation systems within federal jurisdiction (incl. rail) are in Schedule 1.** → cyber-program/incident-response + rail-supplier cyber (IEC 63452/TS 50701). **CHANGING SOON.**
  (Note: 1-day date discrepancy between two law-firm sources; canada.ca release 403'd — exact assent day UNKNOWN[need: primary Public Safety release].)

### Machinery / OHS
- **CSA Z432** — 4th ed. (2023) in force; ~5-yr cycle, next edition not yet announced. **WATCH.**
- **Ontario Reg. 851 PSR** — last changed by O. Reg. 434/21 (eff. 1 Jan 2022); nothing pending found. **STABLE.**

### Rail (Transport Canada)
- **Enhanced Train Control (ETC) Regulations** — proposed; Canada Gazette Part I expected **2026** (60-day comment). → train-control safety + (via CCSPA) cyber; EN 5012x/IEC 63452 for CDN suppliers. **CHANGING SOON.**
- **Railway Personnel Training & Qualifications Regs** — pre-published Gazette I Dec 2024; finalization pending. **WATCH.**
- **No standalone Canadian rail-cyber regulation** — rail cyber arrives via CCSPA designation, not a TC rail-cyber rule. **WATCH.**

---

## Bottom line for FSQ NA
The NA regulatory horizon is **as active as the EU one** and closer to home: **FDA** QMSR + AI-device guidance, **NHTSA** AV framework, **CMMC** phases, **CCSPA now law** (rail in scope), **Health Canada** MDR amendments + MLMD/PCCP. Two things to note vs the site content: (1) Canada's vehicle-cyber regime is still **voluntary** (matches the "export-market clock" framing already on the Automotive page); (2) **AIDA is dead** — Canada has no binding AI law right now, only the voluntary code.

## Provenance caveats
- **CMMC** — conflict RESOLVED 2026-07-24: Phase II **is suspended** (confirmed via DoD primary domains, memo 26-P-1023). Only the exact memo day remains UNKNOWN (Akamai-blocked verbatim PDF).
- Several canada.ca gov pages 403'd automated fetch; CCSPA dates corroborated via BLG/Osler (agree on substance, differ 1 day on assent). US CMMC phase dates partly via Baker Tilly (secondary) quoting the FR rules.
- US AI EO numbers/dates (14179, 14365) and NHTSA AV-STEP withdrawal read off whitehouse.gov / federalregister.gov this session.
