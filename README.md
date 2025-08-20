
# alternative licence


- CLOSE SOURCE PRIVATE:
  - [Closed Software License —  EULA — No-AI](https://github.com/intotheglitched/licence-vs-ai/blob/main/Closed%20Software%20License%20%E2%80%94%20%20EULA%20%E2%80%94%20No-AI.md)<br>_This is good for complety closed project, the private no Ai_

- OPEN SOFTWARE COMPLETELY FREE:
  - [Full FREE Public License — NoAI + Human Supervision](https://github.com/intotheglitched/licence-vs-ai/blob/main/Full%20FREE%20Public%20License%20%E2%80%94%20Open%20software%20%E2%80%94%20%20NoAI%20%2B%20Human%20Supervision.md)<br>_Optimal for open projects, full free (for distribution and users) projects_

- PUBLIC SOFTWARE LIMITED FREE:
  - [Limited FREE Public License — Open Software — NoAI + Human Supervision [2Tier]](https://github.com/intotheglitched/licence-vs-ai/blob/main/Limited%20FREE%20Public%20License%20%E2%80%94%20Open%20Software%20%E2%80%94%20NoAI%20+%20Human%20Supervision%20%5B2tier%5D.md)<br>_Optimal for open projects, free (if distribution is free and is free for users) projects or under €5 million annual incoming_
  - [Limited FREE Public License — Open Software — NoAI + Human Supervision [3Tier]](https://github.com/intotheglitched/licence-vs-ai/blob/main/Limited%20FREE%20Public%20License%20%E2%80%94%20Open%20Software%20%E2%80%94%20NoAI%20%2B%20Human%20Supervision%20%5B3Tier%5D.md)<br>_Optimal for open projects, free (if distribution is free and is free for users) projects or under €2 (tier 2) and €4 million (tier 3) annual incoming_


---


### A simle message from the Author:

<sub>I see companies using our developments without paying us, without giving us any credit or honor.</sub>
<sub>This now includes GitHub, which has moved to the AI branch, and (not official) GitLab.</sub>
<sub>If github don't change policy i try other services, like https://about.gitea.com/</sub>
<sub>Many people don't notice, but everything you do is being stolen without consent.</sub>
<sub>It's outright exploitation, where we are treated as “data for analysis” without seeing how much passion and hours of our lives are spent developing our libraries and frameworks (indie and otherwise).</sub>
<sub>It's unspeakable, someone has to do something... In the meantime, I propose these licenses.</sub>
<sub>Please note: the licenses are provided free of charge and without any legal responsibility regarding their use. Bring the texts to the attention of your lawyers and have them approve their use.</sub>
<br>
<sub>What we want? a honest choose, fee, respect.</sub>
</br>
<sub>Feedback is welcome, follow or star.
<sub>@intotheglitched</sub>

_You can message me for a possible collaboration in this topic_


### Current situation:

| Status | Service                            | Public code used to train AI?                                                       | Private code used to train AI?                                                                                                       | Sell/share data for AI training?                                                                                                                                         | Admin controls / notes                                                                     | Sources                                                                                                                                           |
| ------ | ---------------------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| ❌      | **GitHub (Copilot & platform)**    | **Yes** — Copilot trained on public GitHub repos (historic + stated)                | **No** for Business/Enterprise; **Copilot Free** data may be used **if you enable it**                                               | No selling claimed; data-sharing with providers to serve features                                                                                                        | Org policies; disable/limit Copilot; per-user setting to disallow training in Copilot Free | Copilot page (“trained on public repos”); Terms for Additional Products & Features (Free users training setting). ([GitHub][1], [GitHub Docs][2]) |
| ✅      | **GitLab (GitLab Duo)**            | No (GitLab says it **does not train** generative models on customer data)           | No; inputs/outputs **not retained for training**; zero-retention with vendors                                                        | No                                                                                                                                                                       | Can disable Duo; docs list models & governance                                             | GitLab Duo data usage; GitLab Duo page; AI Transparency Center. ([docs.gitlab.com][3], [about.gitlab.com][4])                                     |
| ✅      | **Bitbucket Cloud (Atlassian)**    | No — Atlassian Intelligence **does not** train on customer data                     | No — applies to Atlassian and third-party AI providers                                                                               | No                                                                                                                                                                       | Admin can turn Atlassian Intelligence off                                                  | Atlassian support “Your data is not used for AI model training”; Trust page. ([Atlassian Support][5], [Atlassian][6])                             |
| ✅      | **JetBrains Space + JetBrains AI** | No                                                                                  | No — “we will **not** use your inputs/data to train AI models”                                                                       | No                                                                                                                                                                       | Org-level controls; optional telemetry (not model training)                                | JetBrains AI Data collection & use; AI Terms of Service. ([JetBrains][7])                                                                         |
| ✅      | **Azure DevOps Repos (Microsoft)** | No                                                                                  | No — Microsoft says **enterprise Copilots/Azure OpenAI** don’t use **Customer Data** to train foundation models (without permission) | No                                                                                                                                                                       | Org controls; standard DPA                                                                 | Microsoft Security Blog FAQ; Azure OpenAI data privacy; M365 Copilot data protection. ([TECHCOMMUNITY.MICROSOFT.COM][8], [Microsoft Learn][9])    |
| ✅      | **AWS CodeCommit (AWS)**           | No evidence CodeCommit content is used for AI training                              | No                                                                                                                                   | AWS AI services may use content for “service improvement” **unless you opt out** (org policy); specific gen-AI services (Bedrock/Q Pro) state **no training by default** | Use **AI-opt-out** policy org-wide; prefer Bedrock/Q **Pro** tiers to avoid training       | AWS AI opt-out policy; Bedrock privacy/FAQ; Amazon Q Developer FAQ. ([Documentazione AWS][10], [Amazon Web Services, Inc.][11])                   |
| ✅      | **Gitea.com (hosted Gitea)**       | No statement of AI training; no built-in AI                                         | No                                                                                                                                   | No                                                                                                                                                                       | N/A                                                                                        | Gitea privacy policy (CommitGo, Inc.). ([Gitea][12])                                                                                              |
| ✅      | **Codeberg (Forgejo-based)**       | No — non-profit; **opposes heavy scraping**; has discussed AI scrapers causing load | N/A                                                                                                                                  | No                                                                                                                                                                       | Anti-scraper stance; infra measures                                                        | Codeberg blog noting AI scrapers/excessive crawling. ([Codeberg News][13])                                                                        |
| ✅      | **SourceHut**                      | **Explicitly prohibited**: ToS/blog ban collecting data to **train ML models**      | N/A                                                                                                                                  | No                                                                                                                                                                       | Enforced by policy                                                                         | “You cannot have our users’ data” (ban on training). ([sourcehut.org][14])                                                                        |

[1]: https://github.com/features/copilot?utm_source=chatgpt.com "GitHub Copilot · Your AI pair programmer"
[2]: https://docs.github.com/en/site-policy/github-terms/github-terms-for-additional-products-and-features?utm_source=chatgpt.com "GitHub Terms for Additional Products and Features"
[3]: https://docs.gitlab.com/user/gitlab_duo/data_usage/?utm_source=chatgpt.com "GitLab Duo data usage"
[4]: https://about.gitlab.com/gitlab-duo/?utm_source=chatgpt.com "GitLab Duo"
[5]: https://support.atlassian.com/rovo/kb/rovo-and-atlassian-intelligence-customer-data-is-not-used-for-ai-model/?utm_source=chatgpt.com "Your data is not used for AI model training - Atlassian Support"
[6]: https://www.atlassian.com/trust/atlassian-intelligence?utm_source=chatgpt.com "Atlassian Intelligence"
[7]: https://www.jetbrains.com/help/ai/data-collection-and-use-policy.html?utm_source=chatgpt.com "Data collection and use policy | JetBrains AI Documentation"
[8]: https://techcommunity.microsoft.com/blog/microsoft-security-blog/faq-protecting-the-data-of-our-commercial-and-public-sector-customers-in-the-ai-/4097231?utm_source=chatgpt.com "FAQ: Protecting the Data of our Commercial and Public ..."
[9]: https://learn.microsoft.com/en-us/azure/ai-foundry/responsible-ai/openai/data-privacy?utm_source=chatgpt.com "Data, privacy, and security for Azure OpenAI Service"
[10]: https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_ai-opt-out.html?utm_source=chatgpt.com "AI services opt-out policies - AWS Organizations"
[11]: https://aws.amazon.com/bedrock/amazon-models/privacy/?utm_source=chatgpt.com "Privacy - AWS - Amazon.com"
[12]: https://about.gitea.com/privacy-policy?utm_source=chatgpt.com "Privacy Policy"
[13]: https://blog.codeberg.org/more-power-for-you-what-a-storage-quota-will-bring.html?utm_source=chatgpt.com "More power for you – what a storage quota will bring"
[14]: https://sourcehut.org/blog/2025-04-15-you-cannot-have-our-users-data/?utm_source=chatgpt.com "You cannot have our user's data"
