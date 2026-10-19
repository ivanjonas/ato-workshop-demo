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
| Vercel project and URL | Project `my-first-site` (`prj_Bh5X69pSIWUrd19ipTT7dqtP8bSO`) created; not deployed |
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
| Vercel deployment | Project created; not deployed | Failed | Deployment API returned 403 because the connection is not authorized for Vercel scope `ato-boy` |

## Current blocker or last change

Exact steps: Created a separate static website folder, added Vercel-ready configuration, saved the setup checkpoint to GitHub branch `work`, and created Vercel project `prj_Bh5X69pSIWUrd19ipTT7dqtP8bSO`.

Expected result: The source is complete enough to open locally and the folder can be imported as a separate Vercel project.

Actual result or error: Source and configuration checks passed. Vercel project creation succeeded. Git linking failed because the Vercel GitHub integration is not installed for `ivanjonas/ato-workshop-demo`. Direct deployment and subsequent project inspection returned 403 because the connection is not authorized for Vercel scope `ato-boy`. The CLI fallback has no authenticated Vercel session. Browser rendering was not observed.

Repairs already attempted and their results: Tried Git-backed project creation, direct source deployment, scoped project inspection, and the supported CLI fallback. The project exists, but deployment requires reauthorizing the Vercel connection for `ato-boy`; Git-triggered deployments additionally require installing Vercel's GitHub integration for the repository.

## Next action

One small task: Reauthorize the Vercel connection for scope `ato-boy`, then deploy the existing project. To enable automatic GitHub deployments, also install Vercel's GitHub integration for `ivanjonas/ato-workshop-demo`.

Completion check: Vercel reports a READY production deployment and its URL serves the placeholder page.

Who owns the next edit: Codex after the owner supplies the content description.

Permissions already given: Create this project under the current GitHub repository and prepare it for Vercel hosting; no production deployment destination has been identified.

## Prompt for a new chat

> Read this state record and the actual current files. I am continuing `my-first-site`. Use my website description to write a brief, scope, and three-increment plan before changing the page. Preserve the Vercel setup and do not alter `my-first-game`.
