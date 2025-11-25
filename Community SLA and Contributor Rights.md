# Community SLA and Contributor Rights

This document is a no-nonsense Community SLA and Contributor Bill of Rights for open source projects. It sets a clear best-practice standards for how open source projects should treat their contributors. Most open source projects run on unpaid labor. Some organizations/projects treat that labor as disposable. This document sets a clear standard for what contributors can reasonably expect, and what maintainers should commit to if they care about establishing healthy community enviroments.


It is written so any project can:

- Adopt it as is
- Adapt it to reality and publish their own version
- Use it as a checklist to stop wasting contributor time


**Status:** v1.1.0 draft – feedback from maintainers and contributors welcome.

Projects are free to adapt this, but if you claim to follow it, you should follow it in practice, not only in words.

The point is not perfection. The point is to establish clear expectations between project and contributor.

---

## 1. Who this is for

- **Project maintainers** who want to treat contributors like adults, not free tech support  
- **Contributors** who are tired of silence, ghosting, and vague promises  
- **Organizations** that claim to care about community and need to prove it

If you run an open source project and say you value contributors, this is one way to show it in writing.

---

## 2. How to use this document

### 2.1 For maintainers

1. Copy this file into your repo as `COMMUNITY-SLA.md`.
2. Edit the response timelines and labels to match your actual capacity.
3. Link it from your `README` and `CONTRIBUTING` docs.
4. Tell contributors you follow it, then actually follow it.

If you cannot meet part of the SLA, say so directly in the file. Honest limits are better than fake promises.

### 2.2 For contributors

- Use this SLA as a lens to evaluate projects you give your time to.  
- Ask projects to adopt or adapt it.  
- If a project consistently ignores the basics in this SLA, you are not obligated to stick around. Take your time and energy somewhere that respects it.

---

## 3. Core principles

1. **Respect for time**  
   Contributor time is not free just because it is not on your payroll.

2. **Predictability over perfection**  
   Clear and consistent response is better than fast one day and silence the next.

3. **Transparency over silence**  
   If priorities change, say so. Do not ghost people.

4. **Safety over growth**  
   No growth goal is worth tolerating harassment or abuse.

5. **Credit over ego**  
   Contributions should be recognized in ways that are visible and meaningful.

---

## 4. Contributor Bill of Rights

Contributors to a project that adopts this standard have the right to:

1. **Acknowledgment of their contributions**  
   - Their name listed in contributors or release notes when their work ships.  
   - Their ideas and reports treated as input, not noise.

2. **Timely response to issues and pull requests**  
   - A first human response within the time frames defined in this SLA.  
   - A clear answer when work will not be merged or is out of scope.

3. **Clear contribution paths**  
   - Up-to-date docs on how to contribute, what is welcome, and what is not.  
   - Clear labels or tags that show what work is starter-friendly or blocked.

4. **A safe environment**  
   - Freedom from harassment, personal attacks, and discrimination.  
   - A Code of Conduct with clear reporting channels and visible outcomes.

5. **Honest communication about project health**  
   - Notice when the project is effectively unmaintained or in low-power mode.  
   - Honest expectations about how likely their work is to be reviewed or shipped.

6. **Attribution and credit**  
   - Their work not silently copied into other branches or products without credit.  
   - The right to be mentioned when their contributions are showcased.

7. **Exit without guilt**  
   - The freedom to step back from contributing without being shamed or pressured.  
   - No expectation of endless free labor.

---

## 5. Project service levels and responsibilities

These are default targets. Projects can adjust them, but they should publish their actual expectations.

### 5.1 Issues

**Goal:** No issue sits without a human response for more than 14 days.

- First human response: within 7 days for most issues, 3 days for security or critical bugs.  
- Initial triage decision: within 14 days. Triage means:
  - Accept as bug or feature,  
  - Mark as question,  
  - Close as out of scope with a short reason.

If the project cannot meet these timelines for a sustained period, it should:

- Mark the repo or parts of it as low-maintenance or archived.  
- Update the `README` or project status to set honest expectations.

### 5.2 Pull requests

**Goal:** No pull request sits without review status for more than 21 days.

- First review or status comment: within 14 days.  
- If the PR is not likely to be merged, maintainers say so clearly and early.

Accepted patterns:

- “Thank you, this is helpful, but not something we plan to merge. Here is why.”  
- “This is a good direction, but we need X changes before we can accept it.”

Not accepted patterns:

- Months of silence.  
- Quietly closing without a reason.  
- Commenting in a way that insults or belittles the contributor.

### 5.3 Questions and support

Projects should clearly state what level of support is realistic.

- If support is “best effort only”, say that upfront.  
- If there is a forum, chat, or mailing list, link it clearly and keep expectations honest.

Suggested minimum:

- Acknowledgment for new questions within 7 days.  
- If the project cannot provide support, point to docs or other resources instead of ignoring people.

### 5.4 Code of Conduct and safety reports

- A named or role-based contact for CoC reports, even if it is a group email.  
- A first acknowledgment of any safety report within 7 days.  
- A clear statement on whether a report is:
  - Accepted and under review,  
  - Not in scope for the project,  
  - Handed off to another body.

Outcomes that affect the community (bans, warnings) should be summarized publicly in a way that protects privacy but shows that the CoC is real.

---

## 6. Contributor responsibilities

A healthy relationship is two-way. Contributors are expected to:

1. **Follow the Code of Conduct**  
   - No harassment, personal attacks, or bad-faith arguments.

2. **Respect maintainer decisions**  
   - Not every suggestion or PR will be accepted.  
   - Debate ideas, not people.

3. **Do reasonable homework before filing**  
   - Check existing issues.  
   - Read the contributing guide.  
   - Provide logs, environment details, and steps to reproduce where needed.

4. **Avoid entitlement**  
   - This is not a paid support contract.  
   - Timelines are targets, not guarantees.

5. **Give clear signals**  
   - If you have to drop a PR or issue, say so.  
   - If you want to take on a task, say that too.

---

## 7. When this SLA is under strain

This SLA is a commitment, not a guarantee. Real life happens. What matters is how gaps are handled.

### 7.1 Maintainer responsibilities when standards slip

If you notice that the timelines or expectations in this SLA are not being met for a sustained period (for example, more than 30 days), maintainers should:

1. **Acknowledge the gap publicly**
   - Add a short note to the `README` or an issue pinned as “Project status”.
   - Example: “We are currently unable to meet our usual response times for issues and PRs. Please expect slower replies.”

2. **Update expectations**
   - Temporarily adjust stated response targets in this SLA to match current capacity.
   - If the project is effectively unmaintained, say so clearly.

3. **Offer a contact for clarification**
   - Provide a role or email (for example, `community@project.org` or `@maintainers` on your chat) where people can ask:  
     > “Is this SLA still in effect? What should contributors expect right now?”

4. **Decide on a path**
   - Either commit to a realistic triage window to catch up,  
   - Or explicitly downgrade your adoption level (for example, from Gold to Minimum).

Silence is not an acceptable response. If the SLA cannot be met, the gap should be visible and named.

---

## 8. Contributor recourse when the SLA is not honored

Contributors are not “nice to have”. They are critical infrastructure. If contributors collectively stop filing issues, reviewing code, answering questions, or writing docs, most projects feel it quickly.

This section names that reality and gives contributors a clear, calm path to respond when the SLA is not being followed.

### 8.1 Slow or no response

If issues or pull requests sit far beyond the published response windows with no human acknowledgement:

1. **Raise it directly and concretely**
   - Open an issue titled something like:  
     `SLA feedback: slow responses on issues/PRs`
   - List a few specific examples: links plus how long they have waited.
   - Ask a clear question, such as:  
     > “Is the SLA still current? Should we adjust expectations?”

2. **Use the published contact channel**
   - If the project lists a community email, forum category, or chat handle, send a short message linking the feedback issue and asking for acknowledgment.

3. **Set a boundary if nothing changes**
   - If there is still no meaningful response after a reasonable window (for example, 14–21 days), contributors are encouraged to:
     - Reduce or pause contributions,  
     - Focus their time on projects that can realistically engage,  
     - State this boundary once in a neutral, factual way.

Example:

> “Given the current response reality, I am going to pause contributions here and put my time into projects that are able to engage. If this changes in the future, I am open to coming back.”

No drama, no harassment, just clear cause and effect.

### 8.2 Dismissive or disrespectful responses

If maintainers are responding, but their replies are consistently dismissive, sarcastic, or hostile, while still claiming to follow this SLA:

1. **Document the pattern, not just one bad reply**
   - Collect a handful of examples (3–5).  
   - Focus on exact quotes and links, not vibes.

2. **Address behavior, not the person**
   - Open an issue or discussion such as:  
     `SLA feedback: tone and respect in maintainer replies`
   - Explain how the responses conflict with the Contributor Bill of Rights.

3. **Reference this SLA directly**
   - For example:  
     > “Section 4 commits to treating contributors with respect and acknowledging their work. These replies feel out of line with that.”

4. **Adjust your engagement if nothing changes**
   - If there is no acknowledgement or improvement:
     - Lower your engagement or leave,  
     - In your own spaces, you can describe your experience in neutral terms, for example:  
       > “I stepped back from contributing to \<project\> because the way feedback was handled did not match their stated community SLA.”

If the behavior crosses into harassment or discrimination, treat it as a **Code of Conduct** issue, not just an SLA concern.

### 8.3 Misalignment between promises and practice

If a project advertises itself as “Gold level” or claims this SLA publicly, but in practice:

- Issues and PRs are regularly ignored,  
- CoC and safety reports go unanswered,  
- Project health is not communicated honestly,

then contributors can:

1. **Ask for a status check**
   - Open a meta or governance issue:  
     `Is the published SLA and adoption level still accurate?`
   - Provide concrete symptoms: stale labels, unanswered CoC contact, long-silent issues.

2. **Invite maintainers to adjust claims**
   - Suggest specific changes, for example:  
     > “It might be more honest to move from Gold to Minimum until there is more maintainer capacity.”

3. **Treat the SLA claims as cosmetic if nothing changes**
   - Assume the project is effectively “no SLA”, and decide if you still want to be there.
   - Give your time to projects that match words with behavior.

### 8.4 Coordinating with other contributors

If multiple contributors see the same SLA gaps and want to respond together:

1. **Start with shared facts**
   - Collect examples in one place (an issue, discussion thread, or document).  
   - Agree on what you are asking for, such as:
     - “An honest downgrade of adoption level”, or  
     - “A focused triage week to clear the backlog”.

2. **Make a calm, collective request**
   - A comment or discussion signed by several contributors carries more weight than scattered complaints.

3. **Consider a quiet pause if there is still no movement**
   - Contributors can agree to temporarily stop filing new issues and PRs and instead:
     - Work on forks,  
     - Move to alternative tools,  
     - Or invest in healthier projects.

This SLA does **not** encourage harassment, campaigns against individuals, or mass-shaming. It recognizes that:

> The most powerful signal contributors have is where they choose to spend their time.

Contributors are allowed to use that power with clear, written boundaries.

### 8.5 Relationship to the Code of Conduct

- Safety issues (harassment, abuse, discrimination) follow the **Code of Conduct** reporting paths first.  
- SLA recourse should not be used as cover for personal attacks, brigading, or revenge.

If both the SLA and the CoC are ignored, the healthiest option is usually to leave and invest in spaces that are capable of being accountable.

---

## 9. Adoption levels

If a project wants to publicly claim alignment with this standard, it should pick the level that matches current reality, not aspiration.

### Level 1: Minimum

- The project adopts the Contributor Bill of Rights (Section 4).  
- It publishes response targets for issues and PRs (Section 5).  
- It has a Code of Conduct with a visible contact method.

### Level 2: Strong

Everything in Minimum, plus:

- Weekly triage of issues and PRs.  
- Release notes that credit contributors.  
- Periodic updates on project health and maintenance status.

### Level 3: Gold

Everything in Strong, plus:

- Structured contributor recognition or a lightweight program.  
- Clear labels and on-ramps for new contributors.  
- At least yearly feedback from contributors with visible follow-through.

If a project falls below a level, it should drop down or update its claim. No one benefits from pretending.

---

## 10. Evolving this standard

This is version 1 of the Community SLA and Contributor Rights standard. It should improve with real input.

You can help by:

- Opening issues with concrete problems or edge cases.  
- Proposing wording changes that keep it simple and honest.  
- Sharing how you adopted or adapted it in your project.

Keep suggestions focused and practical. No corporate fluff, no manifesto bloat.

---

## 11. License

Text and documentation in this file are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

You may copy, adapt, and share this work, provided you give clear attribution to **Michael Ellis** and link back to the source:

> “Based on the Community SLA and Contributor Rights standard by Michael Ellis.”

If you build something useful on top of this, say so and ship it.
