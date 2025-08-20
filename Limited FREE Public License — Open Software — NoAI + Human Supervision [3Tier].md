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
>   – **Tier 2:** > EUR 1,000,000 and ≤ EUR 5,000,000 → notify Licensor; if no agreement in 60 days, default **10%** royalty (cap **EUR 200,000/year**), payable quarterly; reporting per §4(e).
>   – **Tier 3:** > EUR 5,000,000 (or funding/contracts > EUR 5,000,000) → **Distribution Agreement required before** crossing; otherwise rights terminate (§10).
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
| **Tier 2/3** fees/agreements                                                    |    ✓/✖    |              | As per §4(d): default 10% (cap EUR 200k/year) in Tier 2 if no agreement; Tier 3 requires agreement before crossing. |


---

| COST                                                                         | ✓ Allowed | $ Cost | Conditions / Notes                                                                   |
| ------------------------------------------------------------------------------ | :-------: | :----------: | ------------------------------------------------------------------------------------ |
| FOSS project (OSI-approved, public VCS, totally free to end users) | ✓ |  | **FREE** (Ai? read licence) |
| Linux distribution packaging (official repos/mirrors) for totally free to end users  | ✓ |  | **FREE** (Ai? read licence) |
| Tier 1 (≤ EUR 1,000,000 Qualified Revenue, rolling 12 months) | ✓ |  | **FREE** (Ai? read licence) |
| Tier 2 (> EUR 1,000,000 and ≤ EUR 5,000,000) |   | $ | <i>easy distribution, no fear<i><br>**Default fee (if no agreement):** 10% of Qualified Revenue (gross receipts net of VAT and bona fide refunds/chargebacks), **capped at EUR 200,000 per calendar year**; payable quarterly; reporting per §4(e). You may replace this with a signed Distribution Agreement. |
| Tier 3 (> EUR 5,000,000 or funding/contracts > EUR 5,000,000) |  | $ | <i>big tech, big business<i> <br> **Requires a paid Distribution Agreement before crossing the threshold**; absent signature, rights terminate for that Project per §10. Fees negotiated (enterprise terms). |

```

---

### copy into a **LICENCE.md** or **LICENCE.txt**

_change all placeholder: <YEAR(S)>, <AUTHOR/ORG>, <jurisdiction>, <city/province>, and (if you use the “or-later” option) <https://your-domain/licensing>._

```md
```
