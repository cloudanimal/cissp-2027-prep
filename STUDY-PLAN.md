# CISSP 2027 Study Plan

**Target outline:** ISC2 CISSP Exam Outline, effective April 15, 2027
**Plan start:** Monday, October 19, 2026
**Target exam window:** April 26 to May 14, 2027 (a week or two after the new outline goes live)
**Pace:** 5 hours per week, one hour a day, Monday through Friday (about 135 hours total)

## Exam at a glance

| Item | 2027 value |
|---|---|
| Format | Computerized Adaptive Testing (CAT) |
| Length | 3 hours |
| Items | 100 to 150 |
| Passing score | 700 of 1000 |
| Item types | Multiple choice plus advanced items (drag and drop, hotspot) |

| Domain | Weight | Approx. items at 125 |
|---|---|---|
| 1. Security Governance and Risk Management | 13.6% | 17 |
| 5. Identity and Access Management | 13.6% | 17 |
| 3. Security Architecture and Engineering | 12.8% | 16 |
| 4. Communication and Network Security | 12.8% | 16 |
| 7. Security Operations | 12.8% | 16 |
| 2. Asset Security | 12.0% | 15 |
| 6. Security Assessment and Testing | 11.2% | 14 |
| 8. Software Development Security | 11.2% | 14 |

The weights are nearly flat, so there is no safe domain to skip. Every domain is worth between 14 and 17 questions.

## The daily hour

Every weekday session follows one of two shapes, so there is never a question about what to do when you sit down.

| Day | Session |
|---|---|
| Monday to Thursday | 20 minutes of reading or video on the current topic, then 40 minutes of questions with explanations |
| Friday | Review the week's miss log, then flashcards for anything you missed twice |

About 135 hours across 27 weeks is a solid budget for someone with deep field experience. Most of the time goes to questions, not reading, because that is where the mindset gets trained.

## The real challenge for an experienced practitioner

With 20 years in the field, recall is not the problem. The two things that fail experienced candidates:

1. **Answering as the engineer instead of the advisor.** CISSP rewards the answer a risk-focused security manager would give: protect people first, follow policy and process, get management approval, address root cause, and do not touch the keyboard yourself. The technically clever fix is often the wrong answer.
2. **ISC2 vocabulary versus real-world vocabulary.** Terms like due care versus due diligence, the formal BCP/DRP sequence, and data roles (owner, custodian, controller, processor) have exact ISC2 meanings that differ from everyday usage.

Both are trained through practice questions with explanations, not more reading.

## Phase 0: Baseline (week 1, Oct 19 to 25)

- Self-rate every 2027 objective (1.1 through 8.5) on a 1 to 3 scale. The study app will include this checklist.
- Take one 100-question mixed diagnostic to find the gaps by domain.
- Read a "think like a manager" primer (see Resources) before doing any deep study.

## Phase 1: Domain pass (weeks 2 to 14, Oct 26 to Jan 24)

The ordering puts the newest and least practiced material first and saves your home territory for last. The first round of self-ratings may reorder it.

| Weeks | Domain | Why it sits here |
|---|---|---|
| 2 to 3 | D3 Architecture and Engineering | Largest 2027 change set; crypto math, security models, and physical design are rarely exercised in VM work |
| 4 to 5 | D4 Communication and Network | Deep protocol and architecture detail; long objective list |
| 6 to 7 | D8 Software Development Security | SSDF, SBOM, shift left, and maturity models are new or expanded |
| 8 to 9 | D5 IAM | Tied for heaviest weight; access control models and passwordless changes |
| 10 | D2 Asset Security | Data roles and lifecycle vocabulary; asset management is now broader |
| 11 to 12 | D1 Governance and Risk | ISC2 ethics, legal and regulatory, BIA, and quantitative risk formulas (SLE, ALE, ARO) |
| 13 | D6 Assessment and Testing | Close to your daily work; mostly terminology alignment |
| 14 | D7 Security Operations | Home territory; focus on the formal DR, BC, and investigations content |

For each domain:

1. Read the domain chapter in your primary book across the 20-minute reading blocks. Skim what you already do daily and slow down on what you do not.
2. Watch the domain mind map or summary video in one reading block near the end of the domain.
3. Answer about 60 domain questions per week in the 40-minute blocks, and read every explanation, including the ones you got right.
4. Log each miss as either "did not know" or "knew it, picked the engineer answer." The second kind is the one to fix.

## Phase 2: 2027 delta drill and mindset (weeks 15 to 21, Jan 25 to Mar 14)

Third-party books and question banks written for the 2024 outline will not cover these items well, so this phase targets them directly.

**New or materially changed in 2027:**

- **D1:** Ethics in AI; "industry standards" removed as an investigation type; sustaining governance; HIPAA in privacy and risk frameworks; SLAs inside vendor agreements; reputational supply chain risk; measuring the awareness program and stakeholder engagement
- **D2:** Handling requirements (physical, digital, encryption, secure media destruction), which was a bare objective in 2024 and likely carries more questions now; data management policy; asset management policy, retention, and retirement; CNAPP
- **D3:** Well-architected framework; two-person integrity; rotation of duties; privacy-enhancing technologies; HSM; OT alongside ICS; supply chain risk, autonomous systems, and quantum computing as system types; post-quantum cryptography; key management practices; digital signatures and certificates; Adversary-in-the-Middle; zero-day attacks; AI threats (adversarial AI, model poisoning, deepfakes); continuous security review in the lifecycle
- **D4:** Software-defined security (moved here from D8); remote working
- **D5:** Identities as an access target; passwordless (FIDO, WebAuthn, passkeys, biometrics); Risk-Adaptive Access Control (RAdAC); authorization systems in 5.6
- **D6:** Attack simulations (renamed); responsible disclosure (renamed from ethical disclosure); analyzing audit output alongside test output
- **D7:** SOAR; DLP in egress monitoring; Defense in Depth in foundational concepts; data states in resource protection; EDR and XDR; allowlist and denylist; DDoS scrubbing and MSSP; immutable and encrypted backups; warm sites; DR metrics (MTTR, MTBF); "external" replacing "perimeter" in physical security controls
- **D8:** SSDF and SBOM requirements; shift left; memory-safe languages; SCA under open source

**Removed or relocated:** quantum key distribution, IAST, red/blue/purple team wording, 2FA fatigue and insider threat examples, and SLAs from D7 (moved to D1).

Weekly rhythm in this phase: Monday and Tuesday on the delta list (read, then delta-tagged questions), Wednesday and Thursday on timed mixed 50-question sets, Friday on the miss log.

## Phase 3: Exam simulation (weeks 22 to 27, Mar 15 to Apr 25)

- One full-length practice exam per week, split across Monday to Wednesday as three one-hour blocks of about 45 questions each.
- Thursday reviews every miss; Friday is a focused set on that week's weakest domain.
- **Stamina exception:** sit two of the six practice exams as a single unbroken 3-hour session (a weekend works), so exam day is not your first time doing three straight hours. These are the only sessions that break the one-hour rule.
- **Readiness bar:** three consecutive practice exams at 75% or higher on quality banks, with no domain below 65%.
- Book the exam once the bar is met, ideally in late April or early May 2027.
- Final week: light review only, mind maps and your own miss log. No new material.

## Resources

Prefer editions labeled for the April 2027 outline. Several will be published between now and spring 2027; until they are out, the 2024 editions cover most of the content, and the Phase 2 list fills the gap.

| Purpose | Resource |
|---|---|
| Authoritative scope | ISC2 CISSP Exam Outline (April 2027 PDF) |
| Primary book | ISC2 CISSP Official Study Guide (Sybex), newest edition |
| Question bank | ISC2 Official Practice Tests (Sybex), plus the ISC2 official online practice if budget allows |
| Mindset | "Think like a manager" style primers and videos (Kelly Handerhan, Luke Ahmed) |
| Fast review | Destination Certification mind maps; Pete Zerger exam cram videos |
| This project | The cissp-2027-prep app (below) for the 2027 deltas, flashcards, and progress tracking |

## The study app

A static, zero-dependency browser app in the same style as security-plus-prep, planned as a public repo, **cloudanimal/cissp-2027-prep**, on GitHub Pages. It fills the gaps that commercial question banks leave instead of competing with them.

**In v1:**

- **Today view:** the current week, phase, and the session for today.
- **Plan tracker:** all 27 weeks with dates, focus, and a done checkbox.
- **Objective checklist:** every 2027 objective with the changes marked, and a 1 to 3 self-rating.
- **Question bank, batch 1 (Domain 3):** 50 original questions, about half on 2027 changes and nine manager-mindset scenarios. Options are shuffled every time. A flag button marks anything unclear or wrong.
- **Miss log:** misses from this app and from outside banks, each tagged "did not know" or "engineer answer," with filters and a dashboard warning when engineer answers dominate.
- **Flashcards:** 85 cards on ISC2 vocabulary and 2027 terms across all eight domains.
- **Backup:** export and import of all progress as a JSON file.
- **Privacy:** fully local, no network calls.

**Question batches, each landing a week before its domain starts:**

| Batch | Domain | Ready by |
|---|---|---|
| 1 | D3 Architecture and Engineering | Done (v1) |
| 2 | D4 Communication and Network | Nov 2 |
| 3 | D8 Software Development | Nov 16 |
| 4 | D5 IAM | Nov 30 |
| 5 | D2 Asset Security | Dec 14 |
| 6 | D1 Governance and Risk | Dec 21 |
| 7 | D6 Assessment and Testing | Jan 4 |
| 8 | D7 Security Operations | Jan 11 |

**Deliberately left out:** a practice exam mode. A homemade bank would start repeating questions by the third full exam and inflate scores. Phase 3 uses the official practice tests.

**Before announcing the repo:** spot-check at least the first two batches. Flagged questions get fixed in the next batch.
