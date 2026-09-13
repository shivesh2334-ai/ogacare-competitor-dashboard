# OGA Care Competitive Intelligence Report
**Compiled:** 13 September 2026
**Core product benchmarked:** OGA Care (ogacare.in) — AI-native clinic, consultation and prescription platform for small clinics and solo doctors, positioned on AI-assisted e-prescriptions, India-hosted DPDP-aligned compliance, and same-day onboarding (Free / Basic ₹499/mo / Premium ₹2,499/mo / Custom).

---

## 1. Primary competitor — TatvaCare (TatvaPractice)

**Positioning:** ABDM-certified EMR and practice-management platform spanning clinics to hospitals, with telemedicine, billing and analytics in one suite.

- **ABDM/ABHA:** NHA-approved and ABDM-certified, with native ABHA creation built directly into the consultation flow. Also HIPAA-aligned, ISO 27001-accredited and DPDPA-compliant.
- **Customisation & interoperability:** Configurable specialty-specific EMR templates and HL7/FHIR integration with HIS, labs, pharmacies and third-party apps via secure APIs. Migration tooling supports CSV, FHIR and direct database connectors from other EMRs.
- **Scale/marketing:** Self-describes as "India's fastest-growing EMR platform"; runs a heavy content-marketing operation around ABDM compliance urgency (e.g. warning clinics that ABDM mandates are "already rolling out" via HFR/HPR registries and the DHIS incentive scheme).
- **Multilingual Rx / offline:** Not prominently documented in public sources.
- **Weaknesses noted by reviewers:** setup and integrations "may seem challenging" despite strong compliance credentials; AI is not a headline differentiator compared with Eka Care.

**Why it's the primary threat:** TatvaCare occupies almost the same segment as OGA Care (solo doctor → small clinic → hospital) and leads specifically on the dimension OGA Care is currently weakest on in public messaging — certified ABDM/ABHA workflow. Its marketing engine is actively converting undecided clinics using ABDM-compliance fear, which is a direct funnel risk for OGA Care's target customer.

---

## 2. Eka Care

**Positioning:** "AI-native Health OS" spanning a doctor-side EMR (Eka Doc) and a large consumer PHR/health-record app.

- **ABDM/ABHA:** Among the earliest platforms with deep ABHA linkage; patients can create ABHA IDs and access Health Facility/Progress Records; "ABDM Connect" lets providers verify patients via ABHA and exchange records with consent.
- **AI features:** EkaScribe (ambient voice-to-note documentation) and DocAssist (real-time clinical guidance) are core, actively marketed differentiators — the most AI-forward messaging of any competitor tracked.
- **Multilingual prescriptions:** Explicitly marketed ("vernacular prescriptions") alongside contraindication alerts and differential-diagnosis prompts.
- **Distribution:** Two-sided network — patient app + doctor tool — with WhatsApp/SMS-based patient engagement and Google Business "Reserve with Google" booking integration.
- **Limitation surfaced in third-party comparison:** Eka Care's value is strongest when a patient's own doctors are already on the platform and their labs are ABDM-enrolled; outside that network (handwritten Rx, small labs, non-enrolled hospitals), a rival product (Ayu) captures the gap by digitising everything on-device with offline access.

**Read for OGA Care:** Eka Care is the nearest thing to a direct AI-positioning competitor. Where OGA Care can differentiate is bundled billing/GST and same-day, self-serve onboarding — Eka Care's marketing centres on the record-interoperability and AI-scribe story more than practice-management basics.

---

## 3. Practo Ray

**Positioning:** The clinic-management module bolted onto Practo's doctor-discovery marketplace — India's largest patient-discovery network.

- **ABDM/ABHA:** Certified for both HIP and HIU roles; syncs ABHA IDs to Practo's own patient profiles so follow-ups/reports push automatically to the patient's digital health locker.
- **Strengths:** Massive top-of-funnel patient discovery; automated WhatsApp/SMS reminders; integrated payments (online + in-clinic).
- **Weaknesses (consistent across independent reviews and comparison sites):** No AI documentation; basic billing; limited IPD features; vendor lock-in to the Practo ecosystem; pricing is sales-led and described as changing frequently (~₹1,800–₹4,500/month range reported by third parties).
- **2026 market commentary** ranks it as the most commonly used EMR for small Indian clinics by volume, but "best" is separately awarded to AI-first products like HealthPlix/Eka Care for solo doctors.

**Read for OGA Care:** Practo Ray wins on distribution, not product depth. It is the competitor most vulnerable to being displaced on pure product merit (AI, billing sophistication, customisation) if OGA Care can find comparable distribution/visibility.

---

## 4. Other tracked competitors

### MocDoc
Full-stack HMS/EMR (OPD, IPD, pharmacy, lab, billing) with a notable specialty foothold in fertility/IVF clinics. Markets AIIMS/MoHFW guideline-driven treatment and investigation suggestions directly inside the prescription/diagnosis screens — a concrete clinical-decision-support feature. ABDM-oriented, targets NABH-accreditation pathways, and is frequently recommended for hospitals rather than solo practices. Review-site scores run high (~4.8/5), largely on ease of use and integrated billing/lab/pharmacy.

### KareXpert
Jio Platforms-funded enterprise HIMS: HMS + EMR + LIMS + RIS/PACS + pharmacy + telemedicine + connected ambulance on one stack, used by 500+ hospitals across 70+ cities. This is a large, well-capitalised company but not a near-term threat to OGA Care's solo-doctor/small-clinic segment — it is explicitly recommended for large hospitals and multi-specialty chains, not clinics.

**Data-quality flag:** Sources disagree on live ABDM status. A 2023 company press release states KareXpert "completed integration with ABDM." A mid-2026 independent comparison site states ABDM integration is "on the roadmap, not live," records are DPDP Act 2023-aligned, and SOC 2 Type II is "in progress, not yet certified." Treat any current ABDM claim about KareXpert as unverified until confirmed against the NHA's public certification list — don't cite either version in outward-facing material without checking.

### Clinicea
The most customisation-led product tracked. Converts a clinic's existing paper forms/consents into a bespoke digital EMR — described by the vendor as "super-specialised," used across 20+ specialties (strong in aesthetics and IVF) and reportedly used on 5 continents. Multilingual prescriptions and invoices are explicitly offered as part of the customisation service. Sales-led, custom pricing, and implementation is white-glove rather than self-serve — the opposite of OGA Care's same-day sign-up model. No prominent India-specific ABDM/ABHA claim was found in public sources, which is a notable gap for an Indian-market EMR in 2026.

---

## 5. Cross-cutting takeaways for OGA Care

1. **ABDM/ABHA is now table stakes, and OGA Care's public site doesn't show it.** Four of six competitors (TatvaCare, Eka Care, Practo Ray, MocDoc) lead with certified or well-documented ABHA workflows; one (KareXpert) claims it with disputed verification; only Clinicea shares OGA Care's apparent silence on this. Independent market commentary is blunt that "ABDM integration is not optional — it's a baseline requirement for any serious platform" in 2026. This is the single highest-priority gap to close or, if already built, to surface in marketing.
2. **Multilingual/vernacular prescriptions are a real, checkable differentiator** — only Eka Care and Clinicea visibly market this. If OGA Care's AI assistant already supports Indian-language output, it isn't reflected on the public site.
3. **No single competitor combines AI-native drafting + offline-safe billing + same-day self-serve onboarding.** TatvaCare wins on compliance depth, Eka Care on AI/record network, Clinicea on customisation depth, MocDoc/KareXpert on hospital scale — but each trades off simplicity or speed to get there. This combination is OGA Care's clearest available wedge.
4. **Practo Ray is the most product-vulnerable competitor** despite the largest distribution — its own review base repeatedly cites the same three weaknesses (no AI, basic billing, IPD gaps) that map directly onto OGA Care's stated strengths.

---

## 6. Methodology & caveats

- Built from public vendor websites, app-store listings, and third-party comparison/review platforms (Software Finder, Capterra, GetApp, SourceForge, NABH.co, Codingclave, Softpital, Patient Square, Medisray, MedKyo) as of 13 September 2026.
- All competitor claims are vendor self-reported unless a third-party review or comparison site is cited; none were independently verified against primary sources like the NHA's ABDM certification registry.
- Pricing and feature sets in this market change frequently — several comparison sites reviewed explicitly date-stamp their content and note "confirm current readiness with each vendor" before quoting figures externally.
- This is a point-in-time snapshot. See the recurring-tracking note below for how to keep it current.

---

## 7. Keeping this current (recurring tracking)

This chat can't run itself on a schedule — there is no persistent background process here. Two practical ways to make this recurring:

**Option A — Claude Cowork Scheduled Tasks (recommended if you're on a paid plan).**
In Claude Cowork, create a scheduled task (weekly or monthly) with a prompt like:
> "Re-run the OGA Care vs. TatvaCare/Eka Care/Practo Ray/MocDoc/KareXpert/Clinicea competitive scan. Check each vendor's site and recent reviews for changes to ABDM/ABHA status, pricing, AI features, multilingual Rx, and offline support. Update the dashboard and report, and flag anything that changed since the last run."
Cowork scheduled tasks run automatically on the cadence you set and save fresh outputs each time.

**Option B — Manual periodic refresh in this chat.**
Just come back and say "refresh the competitor tracker" every few weeks. I'll re-search and reissue an updated dashboard/report, and can diff it against this baseline if you keep this file.
