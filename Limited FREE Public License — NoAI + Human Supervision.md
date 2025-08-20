# PUBLIC OPEN SOFTWARE LICENSE <br> LIMITED FREE + NO-AI AND HUMAN SUPERVISION

---

### set online in your site a **robot.txt**

```txt
  User-agent: GPTBot
  Disallow: /
  User-agent: Google-Extended
  Disallow: /
```

### set online in your site a **html head**

```html
  <meta name="robots" content="noai, notranslate, noimageai, noarchive, noindex, nofollow">
  <meta name="generator" content="TDM-reserved-by-owner">
```

---
### markdown repository quick notes

```md

# Licence in short

> **Quick notes (summary — not a license)**
> • Scope: Applies to the copy/release that includes **PPL-NoAI-HIL-1.2** (§11). The English license text governs.
> • Third-party code/content: remains under its own licenses/terms (§3).
> • **AI Use**: prohibited on the **Work and Repository Content** (training, fine-tuning, evaluation, embeddings, or automated generation without Meaningful Human Oversight) unless you obtain a **separate paid AI license** from <your-email> (§4(a)).
> • **Project Use**: allowed only with **Meaningful Human Oversight** in production (§4(b)).
> • **Commercial thresholds** (§4(d)):
>   – **Tier 1:** ≤ EUR 1,000,000 Qualified Revenue (rolling 12 months) → fee €0 under this License.
>   – **Tier 2:** > EUR 5,000,000 (or funding/contracts > EUR 5,000,000) → **Distribution Agreement required before** crossing; otherwise rights terminate (§10).
> • **FOSS & Linux Exception** (§4(f)): 100% OSI-licensed, publicly developed, **free-to-end-users** projects, and official Linux distros/mirrors may use/modify/redistribute at **no charge** (No-AI + MHO still apply). Paid hosted/managed offerings (SaaS) are **not** covered and must follow §4(d).
> • **Repository Content**: covers code, commit history, tags, releases, binaries, package registries, issues/PRs, wiki/docs, CI/CD config, metadata owned/controlled by Licensor; redistribution must preserve license/notice; **no scraping/TDM** (§§2–4).
> • **Qualified Revenue**: gross receipts attributable to the Project, **net of VAT/sales taxes and bona fide refunds/chargebacks** only (§4(d)).
> • Compliance & risk: provided **AS IS**, **no support/maintenance**; user responsible for legal/regulatory compliance; not for safety-critical use without fail-safes; not professional advice (§6).
> • Enforcement: indemnification (§7), patent retaliation (§5), audit/reporting (§4(e)), termination/remedies (§10).
> • Contact: licensing queries → <your-email>.


---
| Action                                                                          | ✓ Allowed | ✖ Prohibited | Conditions / Notes                                                                                                  |
| ------------------------------------------------------------------------------- | :-------: | :----------: | ------------------------------------------------------------------------------------------------------------------- |
| View and study the code                                                         |     ✓     |              | Keep notices/license.                                                                                               |
| **Clone/download Repository Content** (code, releases, docs, CI configs)        |     ✓     |              | For uses under this License; preserve license/notice (§2).                                                          |
| Use the Work in a project (on-prem, app, SaaS)                                  |     ✓     |              | **Meaningful Human Oversight** required in production (§4(b)).                                                      |
| Commercial **non-AI** use (≤ Tier 1)                                            |     ✓     |              | Fee €0; keep notices and pass through No-AI/MHO (§2, §4).                                                           |
| Modify / fork the code                                                          |     ✓     |              | State changes and date; add your copyright for your changes.                                                        |
| Redistribute **verbatim** copies                                                |     ✓     |              | Keep `LICENSE`/`NOTICE` and attribution.                                                                            |
| Redistribute **derivatives**                                                    |     ✓     |              | License under PPL-NoAI-HIL or terms **no less protective** of No-AI/MHO (§2).                                       |
| Offer as **SaaS/hosted**                                                        |     ✓     |              | With **Meaningful Human Oversight** of outputs/decisions.                                                           |
| **Scrape/TDM** the Repository Content or docs to build datasets/embeddings      |           |       ✖      | Prohibited (§4(a)–(c)).                                                                                             |
| Fully automated production use **without** human oversight                      |           |       ✖      | Prohibited (§4(b)).                                                                                                 |
| **Training / fine-tuning / evaluation** of AI/ML on the Work/Repository Content |           |       ✖      | Prohibited unless separately licensed (§4(a)).                                                                      |
| Generate code/outputs via automated systems **without** human oversight         |           |       ✖      | Considered “AI Use” → prohibited (§4(a)).                                                                           |
| Remove or weaken **No-AI** / **MHO** clauses                                    |           |       ✖      | Must pass through **intact** in redistributions (§2).                                                               |
| Remove `LICENSE`/`NOTICE` or attribution                                        |           |       ✖      | Must be preserved (§2).                                                                                             |
| Circumvent technical measures enforcing restrictions                            |           |       ✖      | Prohibited (§4(c)).                                                                                                 |
| Use in **safety-critical** systems (medical, avionics, nuclear, life support…)  |     ✓     |              | Only with appropriate fail-safes/redundancies; **all risk on the user** (§6).                                       |
| Demand **support/maintenance** from the author                                  |           |       ✖      | No obligation (§6).                                                                                                 |
| Assert patent claims against Licensor regarding the Work                        |           |       ✖      | Triggers **license termination** (§5).                                                                              |
| Use project name/trademarks as endorsement                                      |           |       ✖      | No trademark rights (§12).                                                                                          |
| Violate **export control/sanctions** laws                                       |           |       ✖      | Compliance is the user’s responsibility (§9).                                                                       |

---

| COST                                                                         | ✓ Allowed | $ Cost | Conditions / Notes                                                                   |
| ------------------------------------------------------------------------------ | :-------: | :----------: | ------------------------------------------------------------------------------------ |
| FOSS project (OSI-approved, public VCS, totally free to end users) | ✓ |  | **FREE** (NO-Ai) |
| Linux distribution packaging (official repos/mirrors) for totally free to end users  | ✓ |  | **FREE** (NO-Ai) |
| Tier 1 (≤ EUR 5,000,000 only for full free open software) | ✓ |  | **FREE** (NO-Ai) |
| Tier 3 (> EUR 5,000,000 or funding/contracts > EUR 5,000,000) |  | $ | <i>big tech, big business<i> <br> **Requires a paid Distribution Agreement before crossing the threshold**; absent signature, rights terminate for that Project per §10. Fees negotiated (enterprise terms). |


```

---

### copy into a **LICENCE.md** or **LICENCE.txt**

_change all placeholder: <YEAR(S)>, <AUTHOR/ORG>, <jurisdiction>, <city/province>, and (if you use the “or-later” option) <https://your-domain/licensing>._

```md

Permissive Public License — NoAI + Human Supervision, Version 1.2
("PPL-NoAI-HIL-1.2")
SPDX-License-Identifier: LicenseRef-PPL-NoAI-HIL-1.2

Copyright (c) <YEAR(S)> <AUTHOR/ORG>
All rights reserved.

This license text is provided in English only and governs your use of the Work.

0. Copyright, Authorship, Moral Rights
The Work is an original work of authorship by the Original Author identified above.
All copyright and related rights are governed by applicable law and international
treaties (including the Berne Convention). Nothing in this license waives or limits
inalienable moral rights (e.g., attribution/paternity and integrity) where such rights
exist. You must preserve copyright notices, author identification, this license text,
and any NOTICE file included with the Work.

Definitions
“Work”: the software and associated materials distributed with this license.
“Licensor”: the Original Author or rightsholder granting this license.
“Original Author”: the person or entity named above.
“Contributor”: anyone who submits modifications or additions to the Work.
“Distribution”: making the Work or Derivative Works available to any third party.
“Derivative Work”: any work based on or incorporating the Work or Substantial Portions.
“Substantial Portions”: portions of non-trivial size or value.
“Project Use”: use of the Work in a product, service, or workflow (including SaaS).
“Meaningful Human Oversight”: a qualified natural person reviews, approves, and takes
responsibility for decisions or outputs materially influenced by the Work.
“AI Use”: (a) training, fine-tuning, evaluating, or otherwise improving any machine-
learning or AI system; (b) creating datasets or vector embeddings from the Work, the
Repository Content, or Substantial Portions; (c) using the Work to generate code or
outputs by automated systems without Meaningful Human Oversight.
“Affiliate”: any entity that controls, is controlled by, or is under common control
with a party.
“Repository Content”: the repository hosting the Work (e.g., GitHub/GitLab) and all
content within or attached to it, to the extent owned or controlled by the Licensor,
including source code, commit history, branches, tags, release artifacts, binaries,
package registries, issues, pull/merge requests, comments, discussions, wiki pages,
documentation, CI/CD configurations, and metadata.

For purposes of Sections 2 and 4, references to the “Work” include the Repository
Content to the extent owned or controlled by the Licensor.

1. Grant of Rights (Permissive)
Subject to Sections 2–13, the Licensor grants you a non-exclusive, worldwide,
royalty-free license to use, copy, modify, and distribute the Work and Derivative
Works, in source or object form, and to make them available to others.

2. Conditions (Notices, Modifications, Pass-through)
(a) Preserve Notices. You must retain this license text, copyright notices, author
names, and any NOTICE file in source distributions; include reasonable attribution
in binary forms.
(b) Modifications. If you modify the Work, add prominent notices stating you changed
the files and the date of change; include your own copyright notice for your changes.
(c) Pass-through. Distributions (including Derivative Works) must be under this
license or terms no less protective of the restrictions in Section 4(a)–(c) and the
mechanisms in Section 4(d)–(f). You may not remove or weaken those terms.

3. Third-Party Components and Repository Items
Third-party code or content included in the Work or in the Repository Content remains
subject to its own licenses or terms. You must comply with those terms in addition to
this license.

4. Use Restrictions and Commercial Thresholds
(a) No AI Use Without Paid License. You may not perform any AI Use of the Work or
the Repository Content, including creation of datasets or embeddings, without a
separate, paid, written license from the Licensor (see any commercial terms the
Licensor may publish).
(b) Human-in-the-Loop for Project Use. Project Use is permitted only with Meaningful
Human Oversight. Fully automated production use without such oversight is prohibited.
(c) No Circumvention. You may not remove, bypass, or circumvent technical measures
that enforce or facilitate compliance with this Section 4 for the Work or the
Repository Content.

(d) Revenue/Scale Trigger (Tiered; Default 10% Royalty if No Agreement).
For a Project in which the Work is a Material Component:
  Tier 1 — up to EUR 1,000,000 in Qualified Revenue (rolling twelve (12) months):
           permitted under this License (subject to all other terms, including the
           No-AI/HIL requirements).
  Tier 2 — above EUR 5,000,000 (rolling twelve (12) months), or cumulative funding/
           grants/binding contracts exceeding EUR 5,000,000 for the Project:
           Licensee must execute a paid Distribution Agreement before crossing the
           threshold; absent a signed agreement, rights under this License terminate
           for that Project as per §10.

  Definitions (for this subsection only):
  • “Qualified Revenue” means gross receipts attributable to the Project, net of VAT/
    sales taxes and bona fide refunds/chargebacks only.
  • “Material Component” means the Work (or Substantial Portions) is used in a manner
    that is non-trivial to the Project’s functionality, performance, or deliverables.
  • “Project” includes all deployments, modules, and services under common control
    (including Affiliates) that together deliver the same product or service.

(e) Reporting and Limited Audit.
Licensee shall retain records reasonably sufficient to evidence compliance with this
Section 4 and threshold calculations. No more than once per calendar year, upon
fifteen (15) business days’ notice, Licensor may have an independent auditor (bound
by confidentiality) review such records solely to verify compliance. Audits occur
during normal business hours and at Licensor’s cost unless a material underpayment
(>10%) is found, in which case Licensee shall also reimburse reasonable audit costs.

(f) FOSS & Linux Distribution Exception.
(i) FOSS Projects. The fees and thresholds in §4(d) do not apply to a “FOSS Project,”
provided all other terms (including No-AI and Human-in-the-Loop) are met. A “FOSS
Project” means a software project that: (1) is licensed in its entirety under an
OSI-approved open-source license; (2) is publicly developed in a commonly accessible
VCS (e.g., GitHub/GitLab); (3) is made available to end users at no charge (no
license/subscription/usage fee for the software itself)—donations and sponsorships
are permitted; and (4) preserves this License, notices, and the No-AI/HIL pass-through
terms in redistributions. This exception does not cover any “Commercial Managed
Offering,” defined as providing paid access to the software as a hosted/managed
service (SaaS or similar) for third parties, which must follow §4(d).
(ii) Linux Distributions. Official Linux distributions and their mirrors may package
and redistribute the Work at no charge, including reasonable patches, provided they
preserve this License and notices and do not enable or authorize AI Use. This does
not imply that a distribution will accept the package under its policies.
(iii) Loss of Eligibility. If a FOSS Project ceases to meet the above criteria (for
example by introducing paid licensing/usage fees or becoming a Commercial Managed
Offering), Licensee must notify Licensor within thirty (30) days. Starting sixty (60)
days after such change, §4(d) tiers apply unless a paid Distribution Agreement is
executed.
(iv) Anti-Evasion. The FOSS Exception does not apply to structures primarily
intended to circumvent §4(d) (e.g., a thin open-source wrapper around a proprietary
or paid service materially delivering the same product).

5. Patent License and Retaliation
(a) Patent Grant. Subject to your compliance with this license, the Licensor grants
you a perpetual, worldwide, non-exclusive, royalty-free patent license to make, use,
sell, offer for sale, import, and otherwise run the Work as distributed by the
Licensor, solely to the extent such rights are necessarily infringed by that
distribution. This grant does not cover AI Use (§4(a)) unless separately licensed.
(b) Retaliation. If you assert in writing that the Work infringes a patent, this
license and the patent license terminate for you upon that assertion.

6. Support, Compliance, High-Risk Uses, No Professional Advice
(a) No Support or Maintenance. The Licensor and Contributors have no obligation to
provide support, maintenance, updates, security patches, compatibility fixes, or
continued availability of the Work. Any assistance is discretionary and may be
withdrawn at any time.
(b) User Compliance. You are solely responsible for ensuring that your use,
modification, integration, and distribution of the Work comply with applicable laws
and third-party rights (including data protection, security, export control, and any
open-source obligations of dependencies). The Work is not designed for legal or
regulatory compliance by default.
(c) High-Risk Disclaimer. The Work is not designed for safety-critical systems
(e.g., medical devices, aviation, nuclear facilities, life support). If you use the
Work in such contexts, you must implement appropriate fail-safes and redundancies
and you assume all risk from such use.
(d) No Professional Advice. The Work and documentation do not constitute legal,
medical, security, or other professional advice.

7. Indemnification
You agree to indemnify, defend, and hold harmless the Licensor and Contributors from
and against any claim, demand, loss, liability, damage, cost, or expense (including
reasonable attorneys’ fees) arising from (i) your use, modification, distribution, or
deployment of the Work; (ii) your breach of this license (including Section 4); or
(iii) your violation of law or third-party rights. The Licensor may participate in
the defense with counsel of its choice at your expense.

8. Disclaimer of Warranties; Limitation of Liability
(a) AS IS. THE WORK IS PROVIDED “AS IS” AND “AS AVAILABLE”, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, ACCURACY, OR
THAT THE WORK WILL BE ERROR-FREE OR SECURE. YOU BEAR THE ENTIRE RISK AS TO USE AND
PERFORMANCE.
(b) Limitation. TO THE MAXIMUM EXTENT PERMITTED BY LAW, THE LICENSOR AND
CONTRIBUTORS SHALL NOT BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY,
PUNITIVE, OR CONSEQUENTIAL DAMAGES; NOR FOR LOSS OF PROFITS, REVENUE, DATA,
GOODWILL, OR BUSINESS INTERRUPTION, ARISING OUT OF OR RELATING TO THIS LICENSE OR
THE USE OF THE WORK, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGES. IN NO EVENT
SHALL THEIR AGGREGATE LIABILITY EXCEED THE GREATER OF EUR 100 OR THE AMOUNTS PAID BY
YOU SPECIFICALLY FOR RIGHTS UNDER THIS LICENSE (IF ANY). NOTHING IN THIS LICENSE
EXCLUDES OR LIMITS LIABILITY WHERE SUCH EXCLUSION OR LIMITATION IS PROHIBITED BY
LAW (INCLUDING WILLFUL MISCONDUCT OR GROSS NEGLIGENCE WHERE NOT WAIVABLE).

9. Export Controls and Sanctions
You must not use, export, or distribute the Work in violation of applicable export,
re-export, or sanctions laws. You represent that you are not a prohibited party.

10. Termination; Cure; Injunctive Relief
Any breach of Sections 2 or 4 terminates this license automatically. If the Licensor
notifies you and you cure within thirty (30) days, your license is reinstated
retroactively once. A subsequent breach causes permanent termination. The Licensor
may seek injunctive or equitable relief for actual or threatened breach of Section 4.

11. Versioning of the Work and of this License
(a) This copy of the Work is licensed under PPL-NoAI-HIL-1.2 as distributed with it.
The Licensor may release later versions of the Work under different terms; such
changes do not affect your rights in copies you already received.
(b) Choose ONE of the following (delete the other):
    [Only-This-Version] This Work is licensed under this license version only.
    — OR —
    [Or-Later] This Work is licensed under PPL-NoAI-HIL version 1.2 or (at your
    option) any later version published by the Licensor at
    <https://your-domain/licensing>.

12. Trademarks; Entire Agreement; Severability; No Waiver
No trademark, trade name, or brand rights are granted. This license is the entire
agreement concerning the Work. If any provision is held unenforceable, the remainder
remains in effect. Failure to enforce is not a waiver.

13. Governing Law and Forum
This license is governed by the laws of <jurisdiction>. Courts of <city/province>
have exclusive jurisdiction, without regard to conflict-of-law rules.

```
