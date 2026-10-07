# DuoSages legal web: rules for Claude

Static legal pages for legal.duosages.com. Plain HTML, no build step.

## Strict guardrails, no exceptions

- **Only edit files in this repository.** Do not create, deploy, link, configure or delete
  anything on Vercel, GitHub settings, Cloudflare/DNS or any other service unless the
  user's message names that exact action. "Configure Vercel" means editing `vercel.json`
  here, nothing more.
- Hosting is the user's own **developerchunk** Vercel account, and the user connects it
  themselves. Never use any other account (Kevin's included).
- Never touch DNS.
- `git push` only with the user's explicit approval for that push.
- If a step fails, stop and report. Never substitute another route.
