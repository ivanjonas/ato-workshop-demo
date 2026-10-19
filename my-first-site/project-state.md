# Project state: resume here

| Field | Value |
| --- | --- |
| Project name and type | `my-first-site` website |
| Owner and intended audience | Owner: repository owner; audience: unknown until brief |
| Local folder or workspace | `/workspace/ato-workshop-demo/my-first-site` |
| GitHub repository and branch | `ivanjonas/ato-workshop-demo`, branch `work` at setup time |
| Version | Setup checkpoint `62965b5` on `origin/work` |
| Last updated | October 19, 2026 |
| Chatbot and route | Codex connected workspace |
| Current lesson and skill | Website setup; awaiting project brief |
| Vercel project and URL | Not linked or deployed |
| Last working copy and how to reopen it | `index.html`; open directly in a browser |

## Goal and agreed scope

Purpose: To be supplied by the owner.

First version includes: A single static website; exact sections and primary action will be set in the brief.

Out of scope: Accounts, payments, databases, customer data, tracking, and paid services unless explicitly discussed and approved later.

## Files the next assistant must receive

- `index.html`
- `vercel.json`
- `README.md`
- `project-state.md`
- The owner's website description when available

## Observed state

| Check | Version and location tested | Passed / Failed / Not tested | Actual observation |
| --- | --- | --- | --- |
| Static source check | Working tree, `index.html` | Passed | File is present and non-empty; repository whitespace check passed |
| Vercel configuration | Working tree, `vercel.json` | Passed | Configuration parses as valid JSON |
| Narrow layout | Working tree, `index.html` | Not tested | Pending browser observation |
| Vercel deployment | Not deployed | Not tested | Vercel account/team authorization is not configured in this workspace |

## Current blocker or last change

Exact steps: Created a separate static website folder, added Vercel-ready configuration, and saved the setup checkpoint to GitHub branch `work`.

Expected result: The source is complete enough to open locally and the folder can be imported as a separate Vercel project.

Actual result or error: Source and configuration checks passed. Browser rendering was not observed. No deployment attempted because no Vercel identity is configured.

Repairs already attempted and their results: None.

## Next action

One small task: Turn the owner's website description into `project-brief.md`, `project-scope.md`, and `project-plan.md` before replacing the placeholder.

Completion check: The visitor, three main sections, primary action, and five observable checks are recorded.

Who owns the next edit: Codex after the owner supplies the content description.

Permissions already given: Create this project under the current GitHub repository and prepare it for Vercel hosting; no production deployment destination has been identified.

## Prompt for a new chat

> Read this state record and the actual current files. I am continuing `my-first-site`. Use my website description to write a brief, scope, and three-increment plan before changing the page. Preserve the Vercel setup and do not alter `my-first-game`.
