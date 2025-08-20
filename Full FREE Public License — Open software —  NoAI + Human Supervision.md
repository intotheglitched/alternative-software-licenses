# PUBLIC OPEN SOFTWARE LICENSE <br> FULL FREE + NO-AI AND HUMAN SUPERVISION

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

  > **Quick notes (summary — not a license)**
  > • Scope: Applies to the copy/release that includes **FFPL-NoAI-HIL-1.2** (§11). The English license text governs.
  > • Free: **No fees, no tiers** — you may use/modify/redistribute (including commercial and hosted uses) **for free** under this License, subject to §4.
  > • Third-party code: remains under its own licenses (§3).
  > • **AI Use**: absolutely prohibited (training, fine-tuning, evaluation, embeddings, or automated generation **without** Meaningful Human Oversight). No exceptions under this License (§4(a)).
  > • **Project Use**: allowed only with **Meaningful Human Oversight** in production; fully automated production use is prohibited (§4(b)).
  > • Redistribution: keep LICENSE/NOTICE and pass through the **No-AI/HIL** terms in derivatives (§2).
  > • Compliance & risk: provided **AS IS**, **no support/maintenance**; user is responsible for legal/regulatory compliance; not for safety-critical use without fail-safes; not professional advice (§6).
  > • Enforcement: indemnification (§7), patent retaliation (§5), termination & remedies (§10).
  > • Contact: licensing queries → <your-email>.
  
  ---
  
  | Action                                                                         | ✓ Allowed | ✖ Prohibited | Conditions / Notes                                                                |
  | ------------------------------------------------------------------------------ | :-------: | :----------: | --------------------------------------------------------------------------------- |
  | View and study the code                                                        |     ✓     |              | Keep notices/license.                                                             |
  | Use the code in a project (on-prem, app, SaaS)                                 |     ✓     |              | **Meaningful Human Oversight** required in production.                            |
  | Commercial **non-AI** use                                                      |     ✓     |              | Free under this License; keep notices and pass through No-AI/HIL terms.           |
  | Modify / fork the code                                                         |     ✓     |              | State changes and date; add your copyright for your changes.                      |
  | Redistribute **verbatim** copies                                               |     ✓     |              | Keep `LICENSE`/`NOTICE` and attribution.                                          |
  | Redistribute **derivatives**                                                   |     ✓     |              | License under FFPL-NoAI-HIL or terms **no less protective** of No-AI/HIL (§2).    |
  | Publish a public fork                                                          |     ✓     |              | Same attribution and pass-through.                                                |
  | Offer as **hosted/managed service (SaaS)**                                     |     ✓     |              | With **Meaningful Human Oversight** of outputs/decisions.                         |
  | Fully automated production use **without** human oversight                     |           |       ✖      | Not allowed. Requires qualified human review/approval and responsibility (§4(b)). |
  | **Training / fine-tuning / evaluation** of AI/ML on the code                   |           |       ✖      | Absolutely prohibited under this License (§4(a)).                                 |
  | Create **datasets** or **vector embeddings** from the code                     |           |       ✖      | Prohibited (§4(a)).                                                               |
  | Generate code/outputs via automated systems **without** human oversight        |           |       ✖      | Considered “AI Use” → prohibited (§4(a)).                                         |
  | Remove or weaken **No-AI** / **HIL** clauses                                   |           |       ✖      | Must pass through **intact** in redistributions (§2).                             |
  | Remove `LICENSE`/`NOTICE` or attribution                                       |           |       ✖      | Must be preserved.                                                                |
  | Circumvent technical measures enforcing the restrictions                       |           |       ✖      | Explicitly prohibited (§4(c)).                                                    |
  | Use in **safety-critical** systems (medical, avionics, nuclear, life support…) |     ✓     |              | Only with appropriate fail-safes/redundancies; **all risk on the user** (§6).     |
  | Demand **support/maintenance** from the author                                 |           |       ✖      | No obligation for support, patches, or continued availability (§6).               |
  | Assert patent claims against the Licensor regarding the Work                   |           |       ✖      | Triggers **license termination** (patent retaliation, §5).                        |
  | Use project name/trademarks as endorsement                                     |           |       ✖      | No trademark rights; written permission required (§12).                           |
  | Violate **export control/sanctions** laws                                      |           |       ✖      | Compliance is the user’s responsibility (§9).                                     |

```

---

### copy into a **LICENCE.md** or **LICENCE.txt**

_change all placeholder: <YEAR(S)>, <AUTHOR/ORG>, <jurisdiction>, <city/province>, and (if you use the “or-later” option) <https://your-domain/licensing>._

```md
Full FREE Public License — NoAI + Human Supervision, Version 1.2
("FFPL-NoAI-HIL-1.2")
SPDX-License-Identifier: LicenseRef-FFPL-NoAI-HIL-1.2

Copyright (c) <YEAR(S)> <AUTHOR/ORG>
All rights reserved.

This license text is provided in English only and governs your use of the Work.

0. Copyright, Authorship, Moral Rights
The Work is an original work of authorship by the Original Author identified above. All copyright and related rights are governed by applicable law and international treaties (including the Berne Convention). Nothing in this license waives or limits inalienable moral rights (e.g., attribution/paternity and integrity) where such rights exist. You must preserve copyright notices, author identification, this license text, and any NOTICE file included with the Work.

Definitions
“Work”: the software and associated materials distributed with this license.
“Licensor”: the Original Author or rightsholder granting this license.
“Original Author”: the person or entity named above.
“Contributor”: anyone who submits modifications or additions to the Work.
“Distribution”: making the Work or Derivative Works available to any third party.
“Derivative Work”: any work based on or incorporating the Work or Substantial Portions.
“Substantial Portions”: portions of non-trivial size or value.
“Project Use”: use of the Work in a product, service, or workflow (including SaaS).
“Meaningful Human Oversight”: a qualified natural person reviews, approves, and takes responsibility for decisions or outputs materially influenced by the Work.
“AI Use”: (a) training, fine-tuning, evaluating, or otherwise improving any machine-learning or AI system; (b) creating datasets or vector embeddings from the Work or Substantial Portions; (c) using the Work to generate code or outputs by automated systems without Meaningful Human Oversight.
“Affiliate”: any entity that controls, is controlled by, or is under common control with a party.

1. Grant of Rights (Full Free; Permissive)
Subject to Sections 2–13, the Licensor grants you a perpetual, non-exclusive, worldwide, royalty-free license to use, copy, modify, and distribute the Work and Derivative Works, in source or object form, and to make them publicly available, including for commercial purposes and as part of hosted services, provided you comply with Section 4.

2. Conditions (Notices, Modifications, Pass-through)
(a) Preserve Notices. You must retain this license text, copyright notices, author names, and any NOTICE file in source distributions; include reasonable attribution in binary forms.
(b) Modifications. If you modify the Work, add prominent notices stating you changed the files and the date of change; include your own copyright notice for your changes.
(c) Pass-through. Distributions (including Derivative Works) must be under this license or terms no less protective of the restrictions in Section 4(a)–(c). You may not remove or weaken those terms.

3. Third-Party Components
Third-party code included in the Work remains subject to its own licenses. You must comply with those terms in addition to this license.

4. Use Restrictions (Absolute No-AI; Human-in-the-Loop)
(a) Absolute No-AI. You may not perform any AI Use of the Work, including creation of datasets or embeddings. No exceptions and no paid alternative under this license.
(b) Human-in-the-Loop for Project Use. Project Use is permitted only with Meaningful Human Oversight. Fully automated production use without such oversight is prohibited.
(c) No Circumvention. You may not remove, bypass, or circumvent technical or contractual measures that enforce or facilitate compliance with this Section 4.

5. Patent License and Retaliation
(a) Patent Grant. Subject to your compliance with this license, the Licensor grants you a perpetual, worldwide, non-exclusive, royalty-free patent license to make, use, sell, offer for sale, import, and otherwise run the Work as distributed by the Licensor, solely to the extent such rights are necessarily infringed by that distribution. This grant does not cover any activity prohibited by Section 4.
(b) Retaliation. If you assert in writing that the Work infringes a patent, this license and the patent license terminate for you upon that assertion.

6. Support, Compliance, High-Risk Uses, No Professional Advice
(a) No Support or Maintenance. The Licensor and Contributors have no obligation to provide support, maintenance, updates, security patches, compatibility fixes, or continued availability of the Work. Any assistance is discretionary and may be withdrawn at any time.
(b) User Compliance. You are solely responsible for ensuring that your use, modification, integration, and distribution of the Work comply with applicable laws and third-party rights (including data protection, security, export control, and any open-source obligations of dependencies). The Work is not designed for legal or regulatory compliance by default.
(c) High-Risk Disclaimer. The Work is not designed for safety-critical systems (e.g., medical devices, aviation, nuclear facilities, life support). If you use the Work in such contexts, you must implement appropriate fail-safes and redundancies and you assume all risk from such use.
(d) No Professional Advice. The Work and documentation do not constitute legal, medical, security, or other professional advice.

7. Indemnification
You agree to indemnify, defend, and hold harmless the Licensor and Contributors from and against any claim, demand, loss, liability, damage, cost, or expense (including reasonable attorneys’ fees) arising from (i) your use, modification, distribution, or deployment of the Work; (ii) your breach of this license (including Section 4); or (iii) your violation of law or third-party rights. The Licensor may participate in the defense with counsel of its choice at your expense.

8. Disclaimer of Warranties; Limitation of Liability
(a) AS IS. THE WORK IS PROVIDED “AS IS” AND “AS AVAILABLE”, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, ACCURACY, OR THAT THE WORK WILL BE ERROR-FREE OR SECURE. YOU BEAR THE ENTIRE RISK AS TO USE AND PERFORMANCE.
(b) Limitation. TO THE MAXIMUM EXTENT PERMITTED BY LAW, THE LICENSOR AND CONTRIBUTORS SHALL NOT BE LIABLE FOR ANY INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, PUNITIVE, OR CONSEQUENTIAL DAMAGES; NOR FOR LOSS OF PROFITS, REVENUE, DATA, GOODWILL, OR BUSINESS INTERRUPTION, ARISING OUT OF OR RELATING TO THIS LICENSE OR THE USE OF THE WORK, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGES. IN NO EVENT SHALL THEIR AGGREGATE LIABILITY EXCEED THE GREATER OF EUR 100 OR THE AMOUNTS PAID BY YOU SPECIFICALLY FOR RIGHTS UNDER THIS LICENSE (IF ANY). NOTHING IN THIS LICENSE EXCLUDES OR LIMITS LIABILITY WHERE SUCH EXCLUSION OR LIMITATION IS PROHIBITED BY LAW (INCLUDING WILLFUL MISCONDUCT OR GROSS NEGLIGENCE WHERE NOT WAIVABLE).

9. Export Controls and Sanctions
You must not use, export, or distribute the Work in violation of applicable export, re-export, or sanctions laws. You represent that you are not a prohibited party.

10. Termination; Cure; Injunctive Relief
Any breach of Sections 2 or 4 terminates this license automatically. If the Licensor notifies you and you cure within thirty (30) days, your license is reinstated retroactively once. A subsequent breach causes permanent termination. The Licensor may seek injunctive or equitable relief for actual or threatened breach of Section 4.

11. Versioning of the Work and of this License
(a) This copy of the Work is licensed under FFPL-NoAI-HIL-1.2 as distributed with it. The Licensor may release later versions of the Work under different terms; such changes do not affect your rights in copies you already received.
(b) Choose ONE of the following (delete the other):
    [Only-This-Version] This Work is licensed under this license version only.
    — OR —
    [Or-Later] This Work is licensed under FFPL-NoAI-HIL version 1.2 or (at your option) any later version published by the Licensor at <https://your-domain/licensing>.

12. Trademarks; Entire Agreement; Severability; No Waiver
No trademark, trade name, or brand rights are granted. This license is the entire agreement concerning the Work. If any provision is held unenforceable, the remainder remains in effect. Failure to enforce is not a waiver.

13. Governing Law and Forum
This license is governed by the laws of <jurisdiction>. Courts of <city/province> have exclusive jurisdiction, without regard to conflict-of-law rules.

```
