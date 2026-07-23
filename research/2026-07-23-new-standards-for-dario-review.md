# New standards for review — FSQ NA website (for Darío)

**Prepared 2026-07-23 for Darío Manzano.** These are the **58 new standards / regulations /
frameworks** that were proposed as NA additions (the green "NA · NEW" chips) and were
**stripped** from the go-live-minimal site so it could ship on original FSQ content only.
This list is so you can review and **add them back one by one** into the bare site once each
is confirmed against real staff capability.

**How this was built:** each entry was researched this session from the issuing body's
official page (ISO, IEC, RTCA/EUROCAE, FDA, EUR-Lex, NIST, etc.). Links are the source. ISO/IEC/
CENELEC/RTCA links point to the official *catalogue* page (the standards themselves are
paywalled — that landing page is the authoritative reference). A free explainer is given as
"Summary link" where useful.

**⚠ Verify-before-publishing flags** (research surfaced uncertainty or very recent change):
- **IMDRF cybersecurity guidance** — the imdrf.org server timed out during research; the link
  was confirmed via search index but should be clicked before publishing.
- **IEC 63452 (rail cyber)** — still an in-development IEC project, not a published standard;
  publication date not confirmed. Present as "emerging".
- **CMMC** — Phase II requirements were **suspended 13 Jul 2026** pending review; Phase I self-
  assessment remains. Recent — re-check status at publish time.
- **CCSPA (Canada)** — reintroduced as Bill C-8; reported Royal Assent 15 Jun 2026; obligations
  phase in by Governor-in-Council order. Re-check.
- Several ISO/IEC/UNECE/NHTSA official pages bot-block automated fetchers (return 403) but are
  live in a normal browser — titles were matched via the search index.

The eight groupings below match the site's "standards wall" rows.

---

## 1 · Functional safety core

### IEC 61511 (process safety, SIS)
- **Full title:** Functional safety — Safety instrumented systems for the process industry sector (Parts 1–3)
- **Issuing body:** IEC
- **Status:** 2nd edition, 2016 (Part 1:2016 + Amd 1:2017; Parts 2 & 3:2016). Current.
- **What it is:** The process-sector implementation of IEC 61508. Part 1 gives requirements for specifying, designing, installing, operating and maintaining a Safety Instrumented System (SIS) so it achieves/maintains a safe process state; Part 2 is application guidance; Part 3 covers hazard/risk analysis for SIL determination.
- **Why relevant:** The definitive functional-safety standard for process-industry safety instrumented systems.
- **Official link:** https://webstore.iec.ch/en/publication/24241
- **Summary link:** https://www.gt-engineering.it/en/technical-standards/en-iec-standards/iec-61511-gt-engineering/

### ISO 25119 (agricultural/forestry machinery functional safety)
- **Full title:** Tractors and machinery for agriculture and forestry — Safety-related parts of control systems (Parts 1–4)
- **Issuing body:** ISO
- **Status:** 2nd edition 2018 (Parts 1–4); Amendments 1 to Parts 3 & 4 in 2020; confirmed 2024. Part 3 revision under development.
- **What it is:** Four-part functional-safety standard for safety-related electrical/electronic/programmable control systems (SRP/CS) on agricultural and forestry machines: general design principles, concept phase, series development (HW/SW), and production/operation/modification. Defines Agricultural Performance Levels (AgPL).
- **Why relevant:** The sector-specific functional-safety standard for ag/forestry machinery control systems.
- **Official link:** https://www.iso.org/standard/69026.html
- **Summary link:** https://en.wikipedia.org/wiki/ISO_25119

### ISO 18497 (autonomous agricultural machinery safety)
- **Full title:** Agricultural machinery and tractors — Safety of partially automated, semi-autonomous and autonomous machinery (Parts 1–4, 2024)
- **Issuing body:** ISO
- **Status:** Current is the four-part ISO 18497:2024 series, superseding the single-document ISO 18497:2018.
- **What it is:** Safety requirements, verification means and information-for-use for ag machinery with automated/autonomous functions: machine design principles (Pt 1), obstacle-protection systems (Pt 2), autonomous operating zones (Pt 3), verification/validation (Pt 4).
- **Why relevant:** The emerging international standard for autonomous agricultural-machine safety (driverless/robotic farm equipment).
- **Official link:** https://www.iso.org/standard/82684.html
- **Summary link:** n/a

### Def Stan 00-56 (UK MoD safety management)
- **Full title:** Defence Standard 00-56 — Safety Management Requirements for Defence Systems (Part 1: Requirements; Part 2: Guidance)
- **Issuing body:** UK Ministry of Defence (DStan)
- **Status:** Part 1 Issue 8 and Part 2 Issue 6, both 14 Oct 2023 (supersede Issue 7/2017; some resellers still list older issues).
- **What it is:** Contractual UK MoD standard setting requirements to achieve, assure and manage the safety of defence products/services/systems across the lifecycle. Proportionality is central (effort commensurate with risk/complexity). Part 1 mandatory; Part 2 guidance.
- **Why relevant:** The mandatory safety-management standard for UK defence procurement.
- **Official link:** https://www.gov.uk/guidance/uk-defence-standardization
- **Summary link:** n/a

---

## 2 · Automotive

### UNECE R157 (ALKS — automated lane keeping)
- **Full title:** UN Regulation No. 157 — Uniform provisions concerning the approval of vehicles with regard to Automated Lane Keeping Systems (ALKS)
- **Issuing body:** UNECE (WP.29)
- **Status:** In force since 22 Jan 2021; amended for higher speeds (to 130 km/h) and heavy vehicles.
- **What it is:** Binding UN type-approval regulation for Level 3 ALKS (system takes primary control on motorways in defined conditions): system safety, HMI/takeover demands, Operational Design Domain, event data recording (DSSAD), cybersecurity/software.
- **Why relevant:** Required to homologate/audit L3 automated-driving vehicles for markets recognising UN regulations.
- **Official link:** https://unece.org/transport/documents/2021/03/standards/un-regulation-no-157-automated-lane-keeping-systems-alks
- **Summary link:** n/a

### ISO 24089 (software update engineering)
- **Full title:** ISO 24089:2023 — Road vehicles — Software update engineering
- **Issuing body:** ISO (with SAE)
- **Status:** Published 2023; Amendment 1:2024.
- **What it is:** Requirements/recommendations for vehicle software-update engineering at organizational and project levels — vehicles, systems, ECUs, infrastructure, update-package assembly/deployment — with safety/cyber risk management for updates.
- **Why relevant:** The engineering standard underpinning UN R156 (SUMS) compliance.
- **Official link:** https://www.iso.org/standard/77796.html
- **Summary link:** https://www.tuvsud.com/en-us/industries/mobility-and-automotive/automotive-and-oem/autonomous-driving/iso-24089-standard-for-automotive-software-update-engineering

### ISO/PAS 8800 (road vehicles safety & AI)
- **Full title:** ISO/PAS 8800:2024 — Road vehicles — Safety and artificial intelligence
- **Issuing body:** ISO
- **Status:** Published Dec 2024. A PAS (Publicly Available Specification), not yet a full IS.
- **What it is:** Addresses safety-related behaviour arising from AI-element insufficiencies/errors in series-production road vehicles: AI safety lifecycle, assurance arguments, data, safety analysis, post-deployment measures. Complements ISO 26262 and ISO 21448 (SOTIF).
- **Why relevant:** Recognised framework to argue AI safety for ML perception/decision functions alongside functional-safety standards.
- **Official link:** https://www.iso.org/standard/83303.html
- **Summary link:** https://www.ul.com/sis/blog/safety-related-systems-road-vehicles-artificial-intelligence-are-addressed-isopas-88002024

### ANSI/UL 4600 (autonomous product safety case)
- **Full title:** ANSI/UL 4600 — Standard for Safety for the Evaluation of Autonomous Products
- **Issuing body:** UL Standards & Engagement (ANSI-approved)
- **Status:** Edition 3, 17 Mar 2023 (Ed.1 2020, Ed.2 2022).
- **What it is:** Goal-based, technology-agnostic standard for building/assessing a safety case for products operating without human supervision (AVs, autonomous trucks, mining/agri): safety-case construction, hazard/risk analysis, testing, tool qualification, autonomy validation, data integrity, HMI, metrics.
- **Why relevant:** The leading North American standard for structuring/evaluating an autonomous-product safety case.
- **Official link:** https://www.shopulstandards.com/ProductDetail.aspx?productId=UL4600_3_S_20230317
- **Summary link:** https://users.ece.cmu.edu/~koopman/ul4600/index.html

### MISRA (C/C++ coding guidelines)
- **Full title:** MISRA C:2025 — Guidelines for the use of the C language in critical systems; MISRA C++:2023 — Guidelines for the use of C++:17 in critical systems
- **Issuing body:** The MISRA Consortium (originated with MIRA Ltd, UK)
- **Status:** MISRA C:2025 (Mar 2025, ~224 guidelines); MISRA C++:2023 (Oct 2023, targets C++17). Earlier editions remain for legacy use.
- **What it is:** Coding guidelines restricting C/C++ to safer, analyzable subsets to reduce undefined behaviour and defects in safety/security-critical embedded software; referenced by functional-safety standards, enforced via static analysis.
- **Why relevant:** Embedded safety-critical software is routinely required to demonstrate MISRA compliance.
- **Official link:** https://misra.org.uk/
- **Summary link:** n/a

### NHTSA cybersecurity best practices (vehicles)
- **Full title:** Cybersecurity Best Practices for the Safety of Modern Vehicles (2022 update)
- **Issuing body:** US NHTSA (US DOT)
- **Status:** Final updated edition Sep 2022 (supersedes 2016). Non-binding voluntary guidance.
- **What it is:** Risk-based guidance on vehicle-lifecycle cybersecurity management for all organizations designing/building vehicles and their electronics/software — 45 general + 23 technical best practices (secure SDLC, ECU security, external ports, diagnostic-tool security).
- **Why relevant:** The reference US federal guidance for benchmarking North-American automotive cybersecurity posture.
- **Official link:** https://www.nhtsa.gov/document/cybersecurity-best-practices-safety-modern-vehicles-2022
- **Summary link:** n/a

---

## 3 · Medical

### EU IVDR 2017/746 (in-vitro diagnostic regulation)
- **Full title:** Regulation (EU) 2017/746 on in vitro diagnostic medical devices (repealing Directive 98/79/EC and Decision 2010/227/EU)
- **Issuing body:** European Parliament & Council (administered via the European Commission)
- **Status:** In force; date of application 26 May 2022, with phased transitional provisions.
- **What it is:** EU framework governing placing IVDs (lab tests, assays, self-tests, companion diagnostics) on the market: risk-based classification, conformity assessment, clinical/performance evidence, notified-body oversight, technical documentation, UDI/traceability, post-market performance follow-up.
- **Why relevant:** Mandatory for EU market access of IVDs — guides conformity assessment and CE-marking.
- **Official link:** https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32017R0746
- **Summary link:** https://health.ec.europa.eu/medical-devices-sector/new-regulations_en

### IEC 62304 (medical device software lifecycle)
- **Full title:** Medical device software — Software life cycle processes
- **Issuing body:** IEC
- **Status:** In force; consolidated Edition 1.1 = IEC 62304:2006+AMD1:2015 CSV.
- **What it is:** Common framework of lifecycle processes for safe design/maintenance of medical-device software — software risk management, planning, architecture, verification, configuration/change management, problem resolution — scaled by software safety class (A/B/C).
- **Why relevant:** The internationally recognized baseline for a controlled, safety-oriented medical-software lifecycle; core to submissions.
- **Official link:** https://webstore.iec.ch/en/publication/22794
- **Summary link:** n/a

### IEC 60601-1 (medical electrical equipment — basic safety)
- **Full title:** Medical electrical equipment — Part 1: General requirements for basic safety and essential performance
- **Issuing body:** IEC
- **Status:** In force; consolidated Edition 3.2 = IEC 60601-1:2005+AMD1:2012+AMD2:2020 CSV.
- **What it is:** Foundational "general" safety standard for medical electrical equipment/systems — electrical, mechanical, thermal, radiation hazards; shock protection; documented risk management. Supplemented by collateral (60601-1-x) and particular (60601-2-x) standards.
- **Why relevant:** Near-universal prerequisite for market access of powered medical devices worldwide.
- **Official link:** https://webstore.iec.ch/en/publication/67497
- **Summary link:** n/a

### IEC 60601-4-5 (medical device cybersecurity)
- **Full title:** Medical electrical equipment — Part 4-5: Guidance and interpretation — Safety-related technical security specifications
- **Issuing body:** IEC
- **Status:** Published 2021. **Note: a Technical Report (TR), i.e. informative guidance, not a normative standard; excludes IVD devices.**
- **What it is:** Technical security specifications for medical devices on medical IT-networks. Building on IEC 62443, it defines security capability levels (SL-C) and the technical capabilities to reach a given level, so the manufacturer/operator security split can be assessed and communicated.
- **Why relevant:** A concrete, testable capability framework for building and evidencing device cybersecurity.
- **Official link:** https://webstore.iec.ch/en/publication/64703
- **Summary link:** n/a

### IEC 81001-5-1 (health software security lifecycle)
- **Full title:** Health software and health IT systems safety, effectiveness and security — Part 5-1: Security — Activities in the product life cycle
- **Issuing body:** IEC (jointly with ISO)
- **Status:** Published 2021; cited by the EU as a candidate harmonized cybersecurity standard under the medical device regulations.
- **What it is:** Defines security activities/tasks across the health-software lifecycle (development, maintenance, post-market), aligned with IEC 62443-4-1: security risk management, secure design/implementation, verification, coordinated vulnerability handling.
- **Why relevant:** The emerging reference secure-development-lifecycle standard for medical/health software, increasingly expected by regulators.
- **Official link:** https://webstore.iec.ch/en/publication/63293
- **Summary link:** n/a

### FDA §524B (premarket cybersecurity for cyber devices)
- **Full title:** Section 524B FD&C Act, "Ensuring Cybersecurity of Devices" (added by the Consolidated Appropriations Act, 2023). Guidance: "Cybersecurity in Medical Devices: Quality System Considerations and Content of Premarket Submissions."
- **Issuing body:** US FDA (statute by US Congress; guidance by FDA/CDRH)
- **Status:** Statutory requirement in force since 29 Mar 2023; implementing final guidance issued 27 Jun 2025.
- **What it is:** Requires sponsors of a "cyber device" to include cybersecurity information in premarket submissions: post-market vulnerability monitoring/disclosure plan, reasonable-assurance security processes, patch/update procedures, and an SBOM.
- **Why relevant:** A mandatory US market-access gate for connected medical devices.
- **Official link:** https://www.fda.gov/regulatory-information/search-fda-guidance-documents/cybersecurity-medical-devices-quality-management-system-considerations-and-content-premarket
- **Summary link:** https://www.fda.gov/medical-devices/digital-health-center-excellence/cybersecurity

### FDA §515C / PCCP (predetermined change control for AI/ML)
- **Full title:** Section 515C FD&C Act ("Predetermined change control plans for devices"). Guidance: "Marketing Submission Recommendations for a Predetermined Change Control Plan for AI-Enabled Device Software Functions."
- **Issuing body:** US FDA (statutory authority via FDORA 2022; guidance by FDA/CDRH)
- **Status:** Final guidance issued Dec 2024 (supersedes Apr 2023 draft). §515C in force.
- **What it is:** A PCCP lets a manufacturer pre-specify future modifications to an AI-enabled device software function plus the methods to develop/validate/implement them and their impact. Once FDA authorizes it, those changes can be made without a new marketing submission.
- **Why relevant:** The FDA pathway for updating AI/ML medical software post-clearance.
- **Official link:** https://www.fda.gov/regulatory-information/search-fda-guidance-documents/marketing-submission-recommendations-predetermined-change-control-plan-artificial-intelligence
- **Summary link:** n/a

### FDA QMSR (21 CFR Part 820)
- **Full title:** Medical Devices; Quality System Regulation Amendments — establishing the Quality Management System Regulation (QMSR), 21 CFR Part 820
- **Issuing body:** US FDA (CDRH)
- **Status:** Final rule 2 Feb 2024; **effective 2 Feb 2026.** In force.
- **What it is:** Amends device CGMP requirements, **incorporating ISO 13485:2016 by reference** as the QMS baseline, plus FDA-specific provisions; renames "Quality System Regulation" to "Quality Management System Regulation." FDA aligned its inspection program (CP 7382.850) from Feb 2026.
- **Why relevant:** Device makers must transition existing Part 820 quality systems to the ISO 13485-harmonized QMSR.
- **Official link:** https://www.fda.gov/medical-devices/postmarket-requirements-devices/quality-management-system-regulation-qmsr
- **Summary link:** https://www.federalregister.gov/documents/2024/02/02/2024-01709/medical-devices-quality-system-regulation-amendments

### MDCG 2019-16 (EU medical device cybersecurity guidance)
- **Full title:** MDCG 2019-16 — Guidance on Cybersecurity for medical devices (Rev.1)
- **Issuing body:** EU Medical Device Coordination Group (MDCG), under the European Commission
- **Status:** Published Dec 2019; Rev.1 Jul 2020. In force (non-binding guidance).
- **What it is:** Interprets the cybersecurity requirements of Annex I of the MDR (EU) 2017/745 and IVDR: pre-market and post-market aspects across secure design, manufacture and post-market surveillance (vulnerability/incident handling in the technical documentation).
- **Why relevant:** Used to meet EU MDR/IVDR cybersecurity conformity expectations for connected/software devices.
- **Official link:** https://health.ec.europa.eu/system/files/2022-01/md_cybersecurity_en.pdf
- **Summary link:** n/a

### Health Canada SOR/98-282 (Medical Devices Regulations)
- **Full title:** Medical Devices Regulations (SOR/98-282), made under the Food and Drugs Act
- **Issuing body:** Government of Canada / Health Canada
- **Status:** Registered 7 May 1998; in force; consolidated text current to 2026 (last amended 1 Jan 2026).
- **What it is:** Core Canadian regulation governing sale/import/advertisement of medical devices. Four risk classes (I–IV) via Schedule I rules, with licensing, QMS (MDSAP/ISO 13485), labelling and post-market obligations scaled to class.
- **Why relevant:** The foundational legal framework to license and maintain devices on the Canadian market.
- **Official link:** https://laws-lois.justice.gc.ca/eng/regulations/sor-98-282/
- **Summary link:** https://www.canada.ca/en/health-canada/services/drugs-health-products/medical-devices.html

### Health Canada PCCP (ML-enabled devices)
- **Full title:** Pre-market guidance for machine learning-enabled medical devices (introducing the PCCP mechanism); with the joint international "Predetermined change control plans for machine learning-enabled medical devices" guiding principles
- **Issuing body:** Health Canada (guiding principles jointly with US FDA and UK MHRA)
- **Status:** Published and in effect (guidance, non-binding).
- **What it is:** A PCCP lets a manufacturer pre-specify, at licensing, changes to an MLMD (within its original intended use) plus verification/validation methods and mechanisms to detect/revert/stop a failing change — allowing planned ML updates without fresh authorization each time.
- **Why relevant:** Lets AI/ML device makers update models post-authorization within a pre-approved, risk-managed envelope.
- **Official link:** https://www.canada.ca/en/health-canada/services/drugs-health-products/medical-devices/application-information/guidance-documents/pre-market-guidance-machine-learning-enabled-medical-devices.html
- **Summary link:** https://www.canada.ca/en/health-canada/services/drugs-health-products/medical-devices/good-machine-learning-practice-medical-device-development/predetermined-change-control-plans-machine-learning-enabled-medical-devices.html

### GMLP (Good Machine Learning Practice — FDA/HC/MHRA)
- **Full title:** Good Machine Learning Practice for Medical Device Development: Guiding Principles
- **Issuing body:** Jointly US FDA, Health Canada, UK MHRA
- **Status:** Published Oct 2021; in effect (guiding principles, non-binding).
- **What it is:** Ten guiding principles for developing safe, effective, high-quality AI/ML-enabled devices — multidisciplinary expertise, good software/data management, representative datasets, model design/validation, human-AI team performance, lifecycle/post-market monitoring.
- **Why relevant:** A shared FDA/HC/MHRA reference framework for advising AI/ML developers across multiple markets.
- **Official link:** https://www.fda.gov/medical-devices/software-medical-device-samd/good-machine-learning-practice-medical-device-development-guiding-principles
- **Summary link:** https://www.canada.ca/en/health-canada/services/drugs-health-products/medical-devices/good-machine-learning-practice-medical-device-development.html

### IMDRF cybersecurity guidance ⚠ (verify link before publishing)
- **Full title:** Principles and Practices for Medical Device Cybersecurity (IMDRF/CYBER WG/N60FINAL:2020)
- **Issuing body:** International Medical Device Regulators Forum (IMDRF), Cybersecurity WG
- **Status:** Final Apr 2020; in effect. Complemented by N70 (legacy devices) and N73 (SBOM), both 2023.
- **What it is:** IMDRF's harmonized, total-product-lifecycle approach to device cybersecurity — shared stakeholder responsibilities, definitions, information-sharing, pre-market and post-market practices.
- **Why relevant:** The international baseline to align a device's cybersecurity program across FDA, EU, Health Canada and other IMDRF members at once.
- **Official link:** https://www.imdrf.org/documents/principles-and-practices-medical-device-cybersecurity — direct PDF: https://www.imdrf.org/sites/default/files/docs/imdrf/final/technical/imdrf-tech-200318-pp-mdc-n60.pdf  *(imdrf.org timed out during research — click to confirm)*
- **Summary link:** n/a

### NMPA pathway (China)
- **Full title:** China medical device registration/approval pathway administered by the NMPA under the Regulations for the Supervision and Administration of Medical Devices (State Council Decree No. 739)
- **Issuing body:** China NMPA (technical review by CMDE)
- **Status:** In force; governing Decree No. 739 effective 1 Jun 2021.
- **What it is:** Route to place a device on the Chinese market. Class I (filing), Class II/III (full dossier + technical review; Class III typically clinical trials). Foreign makers need a China-based agent, home-country approval proof, Chinese-language dossier, and generally in-country type testing for Class II/III. Expedited routes exist (Innovation, Priority, Emergency).
- **Why relevant:** Guides manufacturers through China's distinct classification, local-testing, local-agent and dossier requirements.
- **Official link:** https://english.nmpa.gov.cn/medicaldevices.html
- **Summary link:** https://www.emergobyul.com/resources/chinese-nmpa-regulatory-approval-process-medical-and-ivd-devices

---

## 4 · Aerospace

### DO-326A / ED-202A (airworthiness security process)
- **Full title:** Airworthiness Security Process Specification
- **Issuing body:** RTCA (DO-326A) / EUROCAE (ED-202A) — SC-216 / WG-72
- **Status:** In force; published 2014. A newer DO-326B/ED-202B exists; the "A" revision is the widely-referenced certification baseline.
- **What it is:** Establishes the airworthiness-security process to handle the information-security threat to aircraft safety — identifying, assessing and mitigating Intentional Unauthorized Electronic Interaction (IUEI) across development and certification. The anchor document the DO-356A methods and DO-355 continuing-airworthiness docs build on.
- **Why relevant:** The foundational airworthiness-security process framework for aircraft cyber certification.
- **Official link:** https://www.rtca.org/security/
- **Summary link:** https://www.eurocae.net/product/ed-202a-airworthiness-security-process-specification/

### DO-356A / ED-203A (airworthiness security methods)
- **Full title:** Airworthiness Security Methods and Considerations
- **Issuing body:** RTCA / EUROCAE — SC-216 / WG-72
- **Status:** In force; ED-203A published Jun 2018.
- **What it is:** The concrete methods/techniques to show compliance with the DO-326A process — security risk assessment, security measures, assurance/refutation — supplying the "how" to the process framework's "what."
- **Why relevant:** The practical methods reference to perform and evidence aircraft security risk assessments for certification.
- **Official link:** https://www.rtca.org/security/
- **Summary link:** https://www.eurocae.net/product/ed-203a-airworthiness-security-methods-and-considerations/

### DO-355 / ED-204 (continuing airworthiness security)
- **Full title:** Information Security Guidance for Continuing Airworthiness
- **Issuing body:** RTCA / EUROCAE — SC-216 / WG-72
- **Status:** In force; current revision DO-355A / ED-204A (ED-204A Sep 2020). Referenced in FAA AC 119-1 and Order 8900.1.
- **What it is:** Guidance for maintaining aircraft information security in operation and maintenance, for Design Approval Holders and operators — an acceptable means of compliance keeping in-service IUEI within acceptable safety levels.
- **Why relevant:** Extends cyber-airworthiness support past type certification into fleet operations/maintenance.
- **Official link:** https://www.rtca.org/security/
- **Summary link:** https://www.eurocae.net/product/ed-204a-information-security-guidance-for-continuing-airworthiness/

### DO-330 (tool qualification)
- **Full title:** Software Tool Qualification Considerations
- **Issuing body:** RTCA (EUROCAE ED-215)
- **Status:** In force; published 2011 (DO-178C suite).
- **What it is:** Objectives/guidance for qualifying software tools used in airborne-software development or verification, so a tool's output can be trusted without independent re-checking. Standalone, technology-independent; qualification level driven by the tool's error-insertion/detection potential.
- **Why relevant:** Nearly every DO-178C/DO-278A program uses code generators/verification tools that must be qualified.
- **Official link:** https://www.rtca.org/do-178/
- **Summary link:** n/a

### DO-331 (model-based development)
- **Full title:** Model-Based Development and Verification Supplement to DO-178C and DO-278A
- **Issuing body:** RTCA (EUROCAE ED-218)
- **Status:** In force; published 2011.
- **What it is:** Modifies/adds to DO-178C/DO-278A objectives for model-based development/verification — how models are classified, developed, verified, traced, and how model coverage/simulation credit is handled. Applied together with (not instead of) the core standard.
- **Why relevant:** Modern avionics teams develop with model-based tools (Simulink/SCADE) needing DO-331.
- **Official link:** https://www.rtca.org/do-178/
- **Summary link:** n/a

### DO-333 (formal methods)
- **Full title:** Formal Methods Supplement to DO-178C and DO-278A
- **Issuing body:** RTCA (EUROCAE ED-216)
- **Status:** In force; published 2011.
- **What it is:** Extends DO-178C/DO-278A to let formal methods satisfy certification objectives, including as a verification means replacing certain testing; defines acceptable formal analysis and how it earns credit.
- **Why relevant:** Lets clients claim certification credit for formal verification in high-DAL software.
- **Official link:** https://www.rtca.org/do-178/
- **Summary link:** n/a

### DO-278A (ground/CNS-ATM software)
- **Full title:** Software Integrity Assurance Considerations for CNS/ATM Systems
- **Issuing body:** RTCA (EUROCAE ED-109A)
- **Status:** In force; published 2011 (the ground-system counterpart to DO-178C).
- **What it is:** Objectives to assure ground-based CNS/ATM software has the integrity needed for safety-related use — the non-airborne analogue of DO-178C, scaled by Assurance Level; the same supplements (DO-330/331/332/333) extend it.
- **Why relevant:** Serves ANSP/ATM and ground-infrastructure clients whose software falls under DO-278A.
- **Official link:** https://www.rtca.org/do-178/
- **Summary link:** n/a

### DO-160 (environmental conditions & test)
- **Full title:** Environmental Conditions and Test Procedures for Airborne Equipment
- **Issuing body:** RTCA (EUROCAE ED-14)
- **Status:** In force; current DO-160G (2010) + Change 1; DO-160H planned Mar 2026.
- **What it is:** Standardized environmental test conditions/procedures to show airborne equipment performs under aircraft environmental and EMI conditions (temperature, altitude, vibration, humidity, fluids, RF, lightning, power). Each equipment type is tested against a tailored subset of "environmental categories."
- **Why relevant:** Near-universal environmental-qualification requirement for airborne equipment approval.
- **Official link:** https://www.rtca.org/do-160/
- **Summary link:** n/a

### FAA ASISP (aircraft systems information security) ⚠ (proposed rule)
- **Full title:** Aircraft Systems Information Security / Protection (ASISP) — rulemaking "Equipment, Systems, and Network Information Security Protection" (RIN 2120-AL94)
- **Issuing body:** FAA
- **Status:** NPRM published in the Federal Register 21 Aug 2024 (comments closed 21 Oct 2024) — a **proposed rule, not yet finalized**.
- **What it is:** FAA research/policy/rulemaking to protect aircraft systems/networks from IUEI. Historically applied via case-by-case special conditions on connected aircraft; being consolidated into a proposed rule with standardized info-security requirements for new transport aircraft/engines/propellers, aligning US practice with DO-326A/DO-356A/DO-355.
- **Why relevant:** Prepares US-market clients for the shift from ad-hoc special conditions to a formal FAA aircraft-cybersecurity rule.
- **Official link:** https://www.faa.gov/headquartersoffices/ang/aircraft-systems-information-security-protection-asisp-rd
- **Summary link:** https://www.federalregister.gov/documents/2024/08/21/2024-17916/equipment-systems-and-network-information-security-protection

### EASA AI / learning assurance
- **Full title:** EASA Artificial Intelligence Concept Paper, Issue 2 — Guidance for Level 1 & 2 machine-learning applications
- **Issuing body:** EASA
- **Status:** Issue 2 published Mar 2024; concept-paper/guidance stage under the EASA AI Roadmap; Issue 3 in development.
- **What it is:** EASA's anticipatory guidance for approving AI/ML in aviation safety applications — Level 1 (human augmentation) and Level 2 (human-AI teaming) — developing "learning assurance" (the ML analogue of development assurance), AI explainability/trustworthiness, and ethics-based assessment.
- **Why relevant:** Used to plan a certifiable AI development/assurance approach for avionics/operational ML.
- **Official link:** https://www.easa.europa.eu/en/document-library/general-publications/easa-artificial-intelligence-concept-paper-issue-2
- **Summary link:** https://www.easa.europa.eu/en/newsroom-and-events/news/easa-publishes-artificial-intelligence-concept-paper-issue-2-guidance

---

## 5 · Rail

### IEC 63452 (railway cybersecurity — emerging) ⚠ (in development)
- **Full title:** Railway applications — Cybersecurity (IEC TC 9 project PT 63452)
- **Issuing body:** IEC, TC 9, project team PT 63452
- **Status:** **Emerging / under development** — active IEC project, not yet a published standard; the international successor track to CENELEC TS 50701. Publication date not confirmed.
- **What it is:** Intended to be the first global railway-cybersecurity International Standard across IEC TC 9 scope (high-speed, mainline, freight, urban/metro), internationalising TS 50701 and adapting IEC 62443 — risk-based cybersecurity requirements and lifecycle roles/responsibilities.
- **Why relevant:** Rail operators/suppliers need to prepare for the incoming global rail-cyber baseline (advise on TS 50701 today, IEC 63452 transition).
- **Official link:** https://www.iec.ch/dyn/www/f?p=103:14:405172316768605::::FSP_ORG_ID:28802
- **Summary link:** https://www.alstom.com/press-releases-news/2024/3/towards-first-railway-cybersecurity-international-standard-why-standards-are-important-secure-railways

### EN 50159 (safety-related communication)
- **Full title:** EN 50159:2010 (+A1:2020) — Railway applications — Safety-related communication in transmission systems
- **Issuing body:** CENELEC (link is the official BSI national adoption, BS EN 50159)
- **Status:** In force; 2010 + A1:2020 (supersedes EN 50159-1/-2:2001).
- **What it is:** Requirements for safety-related electronic systems using transmission systems — defensive techniques against communication threats (repetition, deletion, insertion, re-sequencing, corruption, delay, masquerade) so a required SIL can be achieved over the channel; closed and open transmission systems.
- **Why relevant:** The reference standard for proving safe data communication in rail signalling; complements rail cyber (TS 50701/IEC 63452).
- **Official link:** https://knowledge.bsigroup.com/products/railway-applications-communication-signalling-and-processing-systems-safety-related-communication-in-transmission-systems-1
- **Summary link:** n/a

### EN 50155 (rolling-stock electronic equipment)
- **Full title:** EN 50155:2021 — Railway applications — Rolling stock — Electronic equipment
- **Issuing body:** CENELEC (link is the official BSI national adoption, BS EN 50155)
- **Status:** In force; current edition 31 Jul 2021.
- **What it is:** Requirements for design, manufacture, documentation and testing of on-board electronic equipment (control, regulation, protection, diagnostics, energy supply), including HW of safety-related equipment — operating conditions, HW/SW requirements, integration/testing.
- **Why relevant:** The baseline conformity standard for electronic hardware on rail vehicles.
- **Official link:** https://knowledge.bsigroup.com/products/railway-applications-rolling-stock-electronic-equipment-1
- **Summary link:** n/a

---

## 6 · Machinery & industrial

### ISO 12100 (machinery risk assessment)
- **Full title:** ISO 12100:2010 — Safety of machinery — General principles for design — Risk assessment and risk reduction
- **Issuing body:** ISO
- **Status:** In force; 2010 (flagged to be revised). Consolidated the former 12100-1/-2 and 14121-1.
- **What it is:** Basic terminology, principles and methodology for machine-design safety — identifying hazards, estimating/evaluating risks across the machine life cycle, eliminating hazards or achieving adequate risk reduction. The type-A "basic safety standard" underpinning type-B and type-C machine standards.
- **Why relevant:** The master framework for machinery risk assessment underpinning CE marking — the entry point to machinery compliance.
- **Official link:** https://www.iso.org/standard/51528.html
- **Summary link:** n/a

### ISO 10218 (industrial robot safety)
- **Full title:** ISO 10218-1:2025 (industrial robots) & ISO 10218-2:2025 (robot applications and cells)
- **Issuing body:** ISO
- **Status:** In force; 2025 revision — Part 1 Ed.3 (Feb 2025), Part 2 Ed.2 (2025), replacing the 2011 editions. **The 2025 revision absorbs the collaborative-operation content formerly in ISO/TS 15066.**
- **What it is:** Part 1 — inherently safe design, protective measures and information for use of industrial robots (for robot manufacturers). Part 2 — integration/commissioning/operation/maintenance of robot applications and cells (for integrators).
- **Why relevant:** The core global safety standards for industrial and collaborative robots.
- **Official link:** https://www.iso.org/standard/73933.html (Part 1) · https://www.iso.org/standard/73934.html (Part 2)
- **Summary link:** n/a

### ISO/TS 15066 (collaborative robots)
- **Full title:** ISO/TS 15066:2016 — Robots and robotic devices — Collaborative robots
- **Issuing body:** ISO
- **Status:** Technical Specification (2016); as of Jun 2025 flagged to be revised/superseded, its content now incorporated into ISO 10218-1:2025. Still the standing reference for legacy collaborative applications.
- **What it is:** Safety requirements for collaborative industrial robot systems and their work environment — detailed technical criteria including power-and-force-limiting and biomechanical/pain-threshold data for human-robot collaboration.
- **Why relevant:** The authoritative source of cobot safety criteria and the bridge to ISO 10218-1:2025 that absorbs it.
- **Official link:** https://www.iso.org/standard/62996.html
- **Summary link:** n/a

### RED cyber (2014/53/EU delegated cyber)
- **Full title:** Commission Delegated Regulation (EU) 2022/30 supplementing Directive 2014/53/EU (Radio Equipment Directive) re Article 3(3)(d)(e)(f)
- **Issuing body:** European Commission (delegated act under the RED)
- **Status:** In force; cybersecurity requirements **apply since 1 Aug 2025** (postponed from 2024 by Reg. 2023/2444).
- **What it is:** Activates the RED's Article 3(3) essential requirements for internet-connected radio equipment: (d) network protection, (e) personal-data/privacy safeguards, (f) fraud protection. Applies to connected radio equipment, data-processing wearables, toys/childcare radio equipment, transaction-handling equipment. Presumption of conformity via EN 18031-1/-2/-3.
- **Why relevant:** Makes cybersecurity a mandatory condition of CE marking for wireless/IoT products (compliance vs EN 18031).
- **Official link:** https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32022R0030
- **Summary link:** n/a (EUR-Lex text is free)

### CSA Z432 (Canada machine safeguarding)
- **Full title:** CSA Z432:23 — Safeguarding of machinery
- **Issuing body:** CSA Group (National Standard of Canada)
- **Status:** In force; fourth edition 2023 (supersedes 2016/2004/1994).
- **What it is:** Requirements for design, manufacture (incl. rebuild), installation, maintenance, operation and safeguarding of industrial machinery. The 2023 edition is structured around the hierarchy of controls and aligns with ISO standards and ANSI B11.19.
- **Why relevant:** The primary Canadian machine-safeguarding standard referenced by provincial OHS regulators.
- **Official link:** https://www.csagroup.org/store/product/2430287/
- **Summary link:** n/a

### Ontario PSR (pre-start health & safety review)
- **Full title:** Pre-Start Health and Safety Review — Ontario Regulation 851 (Industrial Establishments), s.7, under the Occupational Health and Safety Act
- **Issuing body:** Government of Ontario / Ministry of Labour, Immigration, Training and Skills Development
- **Status:** In force (s.7 as amended, e.g. O. Reg. 434/21).
- **What it is:** Requires a PSR — by a professional engineer or qualified person — before a new/modified apparatus, structure, protective element or process is first operated, where a listed provision applies. A written, engineer-sealed report identifies compliance measures; equipment must not be used until the review is complete and the report provided to the JHSC.
- **Why relevant:** A legally mandated, engineer-sealed gate before machinery can run in Ontario — a core recurring deliverable for Ontario manufacturers.
- **Official link:** https://www.ontario.ca/laws/regulation/900851
- **Summary link:** n/a

---

## 7 · Product cybersecurity

### EU CRA (Cyber Resilience Act, Annex I)
- **Full title:** Regulation (EU) 2024/2847 on horizontal cybersecurity requirements for products with digital elements (Cyber Resilience Act)
- **Issuing body:** European Parliament & Council
- **Status:** In force; main obligations apply **11 Dec 2027**; Art.14 reporting (exploited vulnerabilities/severe incidents) from **11 Sep 2026**; conformity-body notification from 11 Jun 2026.
- **What it is:** Horizontal EU regulation setting mandatory cybersecurity requirements for all products with digital elements (HW/SW), backed by CE marking. **Annex I** = essential requirements: Part I security properties (secure-by-design/default, minimised attack surface, no known exploitable vulns at release, security updates) and Part II vulnerability handling (SBOM, coordinated disclosure, timely free updates). Plus ENISA/CSIRT incident reporting.
- **Why relevant:** CRA conformity/CE marking becomes a mandatory market-access requirement for connected products.
- **Official link:** https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R2847
- **Summary link:** https://digital-strategy.ec.europa.eu/en/policies/cyber-resilience-act

### CCSPA (Canada) ⚠ (recent legislative status)
- **Full title:** Critical Cyber Systems Protection Act
- **Issuing body:** Government of Canada (Parliament)
- **Status:** Originally Bill C-26 (died on the Order Paper); reintroduced as **Bill C-8**, reported Royal Assent **15 Jun 2026**; operator obligations phase in by Governor-in-Council order and regulations. *(Recent — re-check.)*
- **What it is:** Framework protecting "critical cyber systems" across four federally regulated sectors (telecom, finance, energy, transportation). Designated operators must establish a cyber security program, mitigate supply-chain/third-party risk, report incidents to the Canadian Centre for Cyber Security, and comply with cyber security directions; enforced via monetary penalties.
- **Why relevant:** Operators and suppliers in Canada's critical sectors need compliant cyber programs and incident-reporting under a new mandatory regime.
- **Official link:** https://www.parl.ca/legisinfo/en/bill/45-1/c-8
- **Summary link:** https://www.publicsafety.gc.ca/cnt/trnsprnc/brfng-mtrls/prlmntry-bndrs/20250226-1/07-en.aspx

### ISO/IEC 29147 (vulnerability disclosure)
- **Full title:** ISO/IEC 29147:2018 — Information technology — Security techniques — Vulnerability disclosure
- **Issuing body:** ISO/IEC JTC 1
- **Status:** Published; Edition 2 (2018).
- **What it is:** Requirements/recommendations for how vendors receive information about potential product vulnerabilities and disclose resolution information to users — the external-facing side of vulnerability management (receiving capability, report handling, advisories).
- **Why relevant:** Helps manufacturers establish a compliant coordinated vulnerability disclosure process (increasingly demanded by the EU CRA).
- **Official link:** https://www.iso.org/standard/72311.html
- **Summary link:** n/a

### ISO/IEC 30111 (vulnerability handling)
- **Full title:** ISO/IEC 30111:2019 — Information technology — Security techniques — Vulnerability handling processes
- **Issuing body:** ISO/IEC JTC 1
- **Status:** Published; Edition 2 (2019).
- **What it is:** The internal processes to investigate, triage and resolve potential product vulnerabilities — the internal counterpart to ISO/IEC 29147, covering intake through remediation.
- **Why relevant:** Complements 29147 for the end-to-end vulnerability-management capability now expected of manufacturers.
- **Official link:** https://www.iso.org/standard/69725.html
- **Summary link:** n/a

### SBOM — CycloneDX / SPDX
- **Full title:** OWASP CycloneDX (Bill of Materials standard) and SPDX — System Package Data Exchange (ISO/IEC 5962:2021)
- **Issuing body:** CycloneDX — OWASP Foundation; SPDX — The Linux Foundation (ISO/IEC 5962:2021)
- **Status:** Both actively maintained and in wide use; SPDX is a published international standard.
- **What it is:** Two leading machine-readable Software Bill of Materials formats — an inventory of components, libraries and dependencies in software. CycloneDX is a full-stack BOM standard (also SaaS/hardware/VEX); SPDX communicates components, licenses and security references. Support vulnerability tracking, license compliance and supply-chain transparency.
- **Why relevant:** SBOMs are becoming mandatory (EU CRA Annex I, US federal procurement) — help clients generate/manage them in a recognized format.
- **Official link:** https://cyclonedx.org/ · https://spdx.dev/
- **Summary link:** n/a

### NIST CSF 2.0
- **Full title:** The NIST Cybersecurity Framework (CSF) 2.0 (NIST CSWP 29)
- **Issuing body:** NIST
- **Status:** Published 26 Feb 2024 (version 2.0).
- **What it is:** Voluntary, outcome-based framework to understand, assess, prioritize and communicate cybersecurity risk. v2.0 organizes outcomes under six Functions — Govern, Identify, Protect, Detect, Respond, Recover — plus Tiers and Profiles. Descriptive of outcomes, not prescriptive of controls.
- **Why relevant:** A widely adopted baseline to structure client cybersecurity risk-management programs and map to other regulations.
- **Official link:** https://www.nist.gov/cyberframework
- **Summary link:** https://csrc.nist.gov/pubs/cswp/29/the-nist-cybersecurity-framework-csf-20/final

### NIST SP 800-171 (CUI protection)
- **Full title:** NIST SP 800-171 Revision 3 — Protecting Controlled Unclassified Information in Nonfederal Systems and Organizations
- **Issuing body:** NIST
- **Status:** Revision 3 published May 2024 (supersedes Rev.2 of Jan 2021).
- **What it is:** Recommended security requirements to protect the confidentiality of Controlled Unclassified Information (CUI) in nonfederal systems — for system components that process/store/transmit CUI, used in federal contracts. SP 800-171A gives assessment procedures.
- **Why relevant:** Any US federal (esp. defense) supply-chain org handling CUI must implement these — core input to CMMC.
- **Official link:** https://csrc.nist.gov/pubs/sp/800/171/r3/final
- **Summary link:** n/a

### CMMC (US defense supply-chain) ⚠ (Phase II suspended)
- **Full title:** Cybersecurity Maturity Model Certification (CMMC) Program
- **Issuing body:** US Department of Defense (DoD CIO)
- **Status:** Established by 32 CFR Part 170; Phase 1 began 10 Nov 2025. **Phase II requirements suspended 13 Jul 2026 pending review**; Phase I self-assessment remains; DFARS 252.204-7012 safeguarding continues. *(Recent — re-check.)*
- **What it is:** Tiered program requiring defense contractors to demonstrate cybersecurity maturity as a condition of DoD contracts. Level 1 (basic FCI safeguarding, 15 requirements, annual self-assessment); Level 2 (CUI, the 110 NIST SP 800-171 requirements, self- or third-party assessed); Level 3 (higher protection). Results recorded in SPRS.
- **Why relevant:** Defense-industrial-base suppliers need help meeting SP 800-171 and preparing for CMMC assessment.
- **Official link:** https://dodcio.defense.gov/CMMC/
- **Summary link:** https://dodcio.defense.gov/cmmc/About/

### Def Stan 05-138 (UK MoD cyber supplier assurance)
- **Full title:** Defence Standard 05-138, Issue 4 — Cyber Security for Defence Suppliers
- **Issuing body:** UK MoD
- **Status:** Issue 4 first published 23 May 2024; page updated Dec 2025.
- **What it is:** Defines the cyber security measures a supplier must have at each of five cyber risk levels (Not Applicable → Very High), used to manage cyber risk across the MoD supply chain; applies to MoD procurements, suppliers and subcontractors, alongside the DCPP risk-assessment process.
- **Why relevant:** Suppliers bidding for/holding UK MoD contracts must meet the controls required at their assessed risk level.
- **Official link:** https://www.gov.uk/government/publications/cyber-security-for-defence-suppliers-def-stan-05-138-issue-4
- **Summary link:** n/a

### Cyber Essentials (UK)
- **Full title:** Cyber Essentials (and the audited variant, Cyber Essentials Plus)
- **Issuing body:** UK National Cyber Security Centre (NCSC); delivered by IASME
- **Status:** Active government-backed certification scheme.
- **What it is:** The UK Government's minimum recommended cyber security standard, aligned to five technical controls preventing common internet threats: firewalls, secure configuration, security update management, user access control, malware protection. Cyber Essentials is self-assessed; Cyber Essentials Plus adds an independent technical audit.
- **Why relevant:** A widely required baseline (incl. some UK government contracts) clients need to achieve/maintain.
- **Official link:** https://www.ncsc.gov.uk/cyberessentials/overview
- **Summary link:** n/a

---

## 8 · AI assurance

### EU AI Act
- **Full title:** Regulation (EU) 2024/1689 laying down harmonised rules on artificial intelligence (Artificial Intelligence Act)
- **Issuing body:** European Parliament & Council
- **Status:** In force (entered into force 1 Aug 2024). Staggered application: prohibited practices + AI-literacy from 2 Feb 2025; GPAI + governance from 2 Aug 2025; general applicability 2 Aug 2026 (incl. transparency, Annex III high-risk); product-embedded high-risk phasing to 2 Aug 2027.
- **What it is:** The first comprehensive horizontal AI law. Risk-based: unacceptable-risk (prohibited), high-risk (conformity assessment, risk management, data governance, human oversight, logging, CE-type obligations), limited-risk (transparency), minimal-risk. Distinct regime for general-purpose AI models.
- **Why relevant:** Guides makers of AI-enabled safety-critical products through high-risk conformity assessment and CE-marking.
- **Official link:** https://eur-lex.europa.eu/eli/reg/2024/1689/oj/eng
- **Summary link:** https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai

### ISO/IEC TR 5469 (AI in functional safety)
- **Full title:** ISO/IEC TR 5469:2024 — Artificial intelligence — Functional safety and AI systems
- **Issuing body:** ISO/IEC JTC 1/SC 42
- **Status:** Published 2024. **A Technical Report (informative guidance), not a certifiable requirements standard.**
- **What it is:** Describes properties, risk factors, methods and processes for using AI in functional-safety contexts — AI inside a safety function, and non-AI safety functions ensuring safety of AI-controlled equipment, with associated risk factors/methods.
- **Why relevant:** The bridge between AI and classic functional-safety practice (IEC 61508 / ISO 26262).
- **Official link:** https://www.iso.org/standard/81283.html
- **Summary link:** n/a

### ISO/IEC 23894 (AI risk management)
- **Full title:** ISO/IEC 23894:2023 — Information technology — Artificial intelligence — Guidance on risk management
- **Issuing body:** ISO/IEC JTC 1/SC 42
- **Status:** Published 2023 (Edition 1).
- **What it is:** Guidance on managing AI-specific risk for organizations that develop/produce/deploy/use AI — integrating risk management into AI activities, with processes aligned to the ISO 31000 framework.
- **Why relevant:** A recognized, structured AI-risk-management methodology to underpin EU AI Act high-risk assessments and safety cases.
- **Official link:** https://www.iso.org/standard/77304.html
- **Summary link:** n/a

### ISO/IEC 42001 (AI management system)
- **Full title:** ISO/IEC 42001:2023 — Information technology — Artificial intelligence — Management system
- **Issuing body:** ISO/IEC JTC 1/SC 42
- **Status:** Published 2023 (Edition 1).
- **What it is:** The first AI management system standard (AIMS). Specifies requirements for establishing/maintaining/improving an AI Management System (Plan-Do-Check-Act) — a certifiable management-system standard (like ISO 9001/27001) covering governance, ethics, transparency and continuous learning.
- **Why relevant:** The certifiable governance framework to demonstrate responsible-AI management, complementing EU AI Act compliance.
- **Official link:** https://www.iso.org/standard/81230.html
- **Summary link:** https://www.iso.org/home/insights-news/resources/iso-42001-explained-what-it-is.html

---

## 9 · Process & quality

### intacs-scheme assessments (SPICE / Automotive SPICE)
- **Full title:** International Assessor Certification Scheme e.V. (intacs) — assessor certification for SPICE / ISO/IEC 330xx (formerly 15504) and Automotive SPICE process assessments
- **Issuing body:** intacs e.V. (German association); Automotive SPICE assessor certificates issued under intacs by the VDA QMC Automotive SPICE Certification Office
- **Status:** Active, ongoing scheme; recognized worldwide in automotive. Tiered assessor certs (Provisional / Competent / Principal); covers Automotive SPICE v3.1 and v4.0 on ISO/IEC 330xx.
- **What it is:** The international scheme defining requirements, training curricula and examinations to certify process-assessment assessors — mandatory training via registered providers, exams and documented experience, at graded competence levels for SPICE / Automotive SPICE capability assessments.
- **Why relevant:** Certified assessors let FSQ perform the recognized Automotive SPICE process-capability assessments OEMs demand of software/E-E suppliers.
- **Official link:** https://www.intacs.info/
- **Summary link:** https://vda-qmc.de/en/automotive-spice/automotive-spice-zertifizierung/

---

*58 standards · researched 2026-07-23 from issuing-body sources · links verified to resolve this
session except the ⚠-flagged items above. Standards texts themselves are paywalled at ISO/IEC/
RTCA/CENELEC — the linked catalogue pages are the authoritative references.*
