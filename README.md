
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
<sub>This now includes GitHub, which has moved to the AI branch, and (not officially - [read this](https://forum.gitlab.com/t/can-i-opt-out-from-my-code-being-used-as-training-data-in-gitlab-duo/96563/3#:~:text=open%20source%20repositories%2C-,it%20is%20possible%20for%20AI%20vendors%20unrelated%20to%20GitLab%20to%20scrape%20your%20repository%20and%20train%20with%20it,-.%20However%20if) ) GitLab.</sub>
<sub>If github don't change policy i try other services</sub>
<sub>Many people don't notice, but everything you do is being stolen without consent.</sub>
<sub>It's outright exploitation, where we are treated as “data for analysis” without seeing how much passion and hours of our lives are spent developing our libraries and frameworks (indie and otherwise).</sub>
<sub>It's unspeakable, someone has to do something... In the meantime, I propose these licenses.</sub>
<sub>Please note: the licenses are provided free of charge and without any legal responsibility regarding their use. Bring the texts to the attention of your lawyers and have them approve their use.</sub>
<br><br>
<sub>What we want? a honest choose, fee, respect.</sub>
</br><br>
<sub>Feedback is welcome, follow or star.
<sub>@intotheglitched</sub>

_You can message me for a possible collaboration in this topic_


### Current situation (20/08/2025):

During this period, I discovered that the only one with protection against scraping is <a href="https://codeberg.org/">codeberg</a> (which, however, does not accept non-FOSS products). All the others do NOT have “internal protection,” i.e., a privacy flag that opens the code only to those registered on the site as protection against indiscriminate scraping and even AI grabbing for machine learning.

“Public does not mean to be usurped.”

I’ll set up the table with eight services and organize by columns:

🛡️ Members-only/login wall for browsing "public" repos<br>
- Service
- Default exposure of public repos (anonymous scraping)
- Trains on hosted public code?
- Notes (Enterprise/self-host options)
- Sources

For the “Members-only wall” column:<br>
- Codeberg: ✅ “Limited” profile visibility, restricting access to logged-in users only.
- GitLab (SaaS): ❌ No internal wall on GitLab.com.
- GitLab (Self-Managed/Dedicated): ✅ “Internal” visibility available.
- GitHub (github.com general): ❌ Only enterprise version offers “internal” repositories.

I'll include a note on Enterprise Cloud internal gating.<br>
- GitHub Enterprise Cloud: ✅ internal repos available.
- Bitbucket Cloud: ❌ only public/private options.
- Azure DevOps Services: ❌ public accessible globally, no login wall.
- AWS CodeCommit: N/A, no public repos.
- Gitea.com: ❌ (self-hosted supports sign-in gating).
- SourceHut: ❌ no login wall but anti-ML in ToS.
- Scraping countermeasures: For example, Codeberg uses Anubis (bypassed).

Also, GitHub trains on hosted public code. GitLab does not.


| 🛡️ Members-only wall?                                                     | Service                                           | “Internal / Limited” option that blocks anonymous scraping                                                                                              | Default exposure of public repos                                                                                          | Trains on hosted **public code**?                                                                                                                                   | Notes (controls / nuance)                                                                                                                                                                 | Sources                                                                                                                                               |
| -------------------------------------------------------------------------- | ------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| ✅                                                                          | **Codeberg (Forgejo)**                            | **Yes** — “**Limited profile visibility**” makes all *non-private* repos visible **only to logged-in users** (a login wall).                            | Without “Limited”, public repos are world-readable; with “Limited” they’re member-only. Codeberg is FOSS-first (see FAQ). | **No** — fights AI scrapers; not an AI trainer.                                                                                                                     | Uses anti-scraping measures (e.g., Anubis tarpit; scrapers have tried to bypass). FOSS-only hosting mission.                                                                              | Limited/profile visibility; anti-scraping; FOSS policy; incident report. ([docs.codeberg.org][1], [The Register][2])                                  |
| ❌ *(SaaS)* / ✅ *(Self-Managed/Dedicated)*                                  | **GitLab (GitLab.com vs Self-Managed/Dedicated)** | **GitLab.com:** **No** “internal” visibility. **Self-Managed/Dedicated:** **Yes** — “**Internal**” visibility (login-required for instance members).    | GitLab.com public repos are world-readable; Self-Managed/Dedicated can gate via “Internal.”                               | **No** — “Model input/output is never used to train,” and **GitLab does not train models**.                                                                         | Duo uses Anthropic/Google/Fireworks with zero/limited retention; admin controls; prompt caching opt-out.                                                                                  | Internal visibility scope; data-use statements; transparency center. ([docs.gitlab.com][3], [about.gitlab.com][4])                                    |
| ❌ *(for general users)* / ✅ *(Enterprise only)*                            | **GitHub**                                        | **Enterprise Cloud orgs** have **Internal** repos (visible to enterprise members only). General github.com has only public/private for most orgs/users. | Public repos are world-readable (no login wall).                                                                          | **Yes (pre-training)** — Copilot trained *in part* on public GitHub code.                                                                                           | No per-repo opt-out for excluding public repos from historical training; controls = block suggestions matching public code; enterprise “no training on your prompts/outputs” commitments. | Repo visibility docs; Internal repos (Enterprise); FSF explainer on training on public GitHub code. ([GitHub Docs][5], [Free Software Foundation][6]) |
| ❌                                                                          | **Bitbucket Cloud (Atlassian)**                   | No “internal/login-wall” mode; only public/private.                                                                                                     | Public repos are world-readable.                                                                                          | **No** — Atlassian states customer data isn’t used to train AI models/services.                                                                                     | Org admins can disable AI features; Rovo indexes workspace data but training across customers is disallowed.                                                                              | Privacy and “no training” statements; repo visibility docs. ([Atlassian Support][7], [atlassian.com][8])                                              |
| ❌                                                                          | **Azure DevOps Repos (Microsoft)**                | No “members-only public” mode; projects are **public or private**.                                                                                      | Public projects are world-readable; private are restricted.                                                               | **No evidence** of training on hosted public Azure DevOps repos; Microsoft says **Customer Data** isn’t used to train Copilots/Azure OpenAI **without permission**. | Applies to Microsoft Copilots/Azure OpenAI policies when used alongside DevOps.                                                                                                           | Public vs private projects; Microsoft data-use FAQ. ([Microsoft Learn][9])                                                                            |
| ✅ *(private-only)*                                                         | **AWS CodeCommit**                                | **Effectively a wall** — **no public repositories**; access via IAM only.                                                                               | No anonymous access; nothing to scrape.                                                                                   | N/A for hosted *public* code (there is none).                                                                                                                       | Service is now closed to new customers but existing users continue; IAM controls govern access.                                                                                           | No public repos; IAM access; service note. ([AWS Documentazione][10], [Stack Overflow][11])                                                           |
| ❌ *(on hosted gitea.com)* / ✅ *(if self-hosting Gitea and you turn it on)* | **Gitea.com (hosted Gitea)**                      | Hosted gitea.com: **No** login wall for public. **Self-hosted Gitea** can enable `REQUIRE_SIGNIN_VIEW=true` (instance-wide login-required).             | By default, public repos are world-readable.                                                                              | **No statement** that hosted gitea.com trains on user code.                                                                                                         | Self-hosted admins can force sign-in view; hosted service focuses on standard hosting.                                                                                                    | Require-signin config; Gitea docs. ([Gitea][12], [docs.gitea.com][13])                                                                                |
| ❌                                                                          | **SourceHut (sr.ht)**                             | No built-in login wall for public repos.                                                                                                                | Public repos are world-readable.                                                                                          | **No** — explicit policy **forbids automated collection for ML training**.                                                                                          | Strong anti-scraping stance in policy; community enforcement.                                                                                                                             | “You cannot have our users’ data.” ([sourcehut.org][14])                                                                                              |

[1]: https://docs.codeberg.org/collaborating/repo-permissions/?utm_source=chatgpt.com "Repository Permissions"
[2]: https://www.theregister.com/2025/08/15/codeberg_beset_by_ai_bots/?utm_source=chatgpt.com "Codeberg beset by AI bots that now bypass Anubis tarpit"
[3]: https://docs.gitlab.com/user/public_access/?utm_source=chatgpt.com "Project and group visibility"
[4]: https://about.gitlab.com/ai-transparency-center/?utm_source=chatgpt.com "GitLab AI Transparency Center"
[5]: https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories?utm_source=chatgpt.com "About repositories"
[6]: https://www.fsf.org/licensing/copilot/copyright-implications-of-the-use-of-code-repositories-to-train-a-machine-learning-model?utm_source=chatgpt.com "Copyright Implications of the Use of Code Repositories to ..."
[7]: https://support.atlassian.com/rovo/kb/rovo-and-atlassian-intelligence-customer-data-is-not-used-for-ai-model/?utm_source=chatgpt.com "Your data is not used for AI model training - Atlassian Support"
[8]: https://www.atlassian.com/trust/atlassian-intelligence?utm_source=chatgpt.com "Atlassian Intelligence"
[9]: https://learn.microsoft.com/en-us/azure/devops/organizations/projects/make-project-public?view=azure-devops&utm_source=chatgpt.com "Change project visibility to public or private - Azure ..."
[10]: https://docs.aws.amazon.com/codecommit/latest/userguide/auth-and-access-control.html?utm_source=chatgpt.com "Authentication and access control for AWS CodeCommit"
[11]: https://stackoverflow.com/questions/48266577/aws-codecommit-public-repository?utm_source=chatgpt.com "AWS CodeCommit Public Repository - git"
[12]: https://forum.gitea.com/t/hiding-users-from-public-view/112?utm_source=chatgpt.com "Hiding users from public view"
[13]: https://docs.gitea.com/administration/config-cheat-sheet?utm_source=chatgpt.com "Configuration Cheat Sheet"
[14]: https://sourcehut.org/blog/2025-04-15-you-cannot-have-our-users-data/?utm_source=chatgpt.com "You cannot have our user's data"


cit github _By default, GitHub, its affiliates, and third parties will not use your data, including prompts, suggestions, and code snippets, for AI model training. This is reflected in your personal settings for GitHub Copilot and cannot be enabled. ([link](https://docs.github.com/en/copilot/how-tos/manage-your-account/manage-policies?utm_source=chatgpt.com#model-training-and-improvements)_ But the CEO has resigned and [Microsoft is launching into AI](https://www.cnbc.com/2025/08/11/microsofts-github-chief-is-leaving-competition-ramps-up-in-ai-coding.html#:~:text=Microsoft's%20GitHub%20chief%20is%20leaving%20as%20competition%20ramps%20up%20in%20AI%20coding%20market&text=Thomas%20Dohmke%2C%20who%20has%20been,part%20of%20Microsoft's%20CoreAI%20group.). Among major forges, GitHub is the one that explicitly acknowledges training. on hosted public GitHub repos and doesn’t offer a repo-level “do not train” flag. On the hoder hands GitLab, Atlassian, Microsoft (Azure DevOps), AWS CodeCommit, Gitea, SourceHut, Codeberg: no evidence they train on your hosted public repos; several publish explicit no-training commitments or even ban ML scraping. 

You can limit github + copilot grabbing code in these ways:

<table>
<tr>
<td width="33%"><img src=https://raw.githubusercontent.com/intotheglitched/alternative-software-licenses/refs/heads/main/images/copilot.disabled.3.png></td>
<td width="33%"><img src=https://raw.githubusercontent.com/intotheglitched/alternative-software-licenses/refs/heads/main/images/copilot.not.disable.2.png></td>
<td width="33%"><img src=https://raw.githubusercontent.com/intotheglitched/alternative-software-licenses/refs/heads/main/images/copilot.not.disable.png></td>
</tr>
</table>

and it is easy to understand that it cannot be completely disabled (you cant).
However... **Those toggles only apply to Copilot's “your usage data” (prompts, suggestions, and small snippets you send/receive while using Copilot). They don't change the fact that Copilot's models were pre-trained on public code (including public GitHub repos). I was not asked for permission, I was not paid, and to me this is tantamount to data theft.**


Helpful legal note (EU): In the EU, the TDM exception in Art. 4 of the DSM Directive allows data mining unless there is an "appropriate" opt-out (including machine-readable data): <b>if you don't reserve the rights, your public content can be used for training - everywere</b>. This is an evolving topic (debate on switching to opt-in). (cit: legalblogs.wolterskluwer.com, Morrison Foerster, PC Gamer)

<b>All your public code is shared for Ai without a licence</b>
