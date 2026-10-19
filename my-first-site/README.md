# My First Site

This folder is the website project inside the `ato-workshop-demo` repository. It follows the course's small static-site route: brief, scope, plan, build, check, save to GitHub, and publish with Vercel.

## Current state

- `index.html` is a temporary, responsive setup page.
- `vercel.json` supplies version-controlled static-site settings.
- Vercel project `my-first-site` is deployed to production at `https://my-first-site-ato-boy.vercel.app/`.
- The production deployment is protected by the team's Vercel Authentication setting.
- The first release was uploaded from repository commit `be581cb`; automatic Git-triggered deployments are not currently linked.
- The content brief, final page structure, and primary action are intentionally undecided until the website description is provided.

## Local check

Open `index.html` directly in a browser. No installation, framework, server, API key, or build command is required.

## Vercel import settings

Import the existing GitHub repository into a **new Vercel project** with these settings:

| Setting | Value |
| --- | --- |
| Root Directory | `my-first-site` |
| Framework Preset | Other |
| Build Command | Leave empty / override with no command |
| Output Directory | Leave empty (the project root contains `index.html`) |
| Install Command | Leave empty |

The first deployment is a public production deployment unless the selected Vercel account or team has additional access controls. A private GitHub repository does not make the deployed website private.

Do not reuse the Vercel project for `my-first-game`; keep the two projects and deployment settings separate.
