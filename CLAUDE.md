# App-development

## How to reply to me

Start every reply with a single bold sentence that names the most important
thing: the result, the blocker, or the decision you need from me. Then write
the normal answer below it.

Example:

> **Deployed and live at loenberegner.vercel.app, but I could not open the page
> myself to verify it.**
>
> ...the rest of the answer...

This applies to short replies too, not just long ones. If the most important
thing is a question, lead with the question.

## What this project is

A single-page Danish pay calculator (lønberegner) in `index.html`. You enter
shifts as weekday + from/to times, and it works out gross pay from a base
hourly rate plus shift supplements.

- Plain HTML, CSS and vanilla JavaScript in **one file**. No npm, no build
  step, no frameworks, no external libraries. Keep it that way.
- Runs entirely in the browser. No backend, and nothing is stored or sent
  anywhere.
- Danish formatting throughout: comma as decimal separator, two decimals,
  `kr.` after the amount. Inputs accept both `7,5` and `7.5`.
- Mobile-first: tap targets at least 52 px tall, numeric keyboard on number
  fields, readable on a phone.
- Code is commented in Danish so it can be followed by a non-programmer. Keep
  new code commented the same way.

## Deployment

Deployed to Vercel as the project `loenberegner`
(https://loenberegner.vercel.app), on team `newproject-9e53747e`.

The Vercel project is **not** connected to GitHub — files were uploaded
directly. A `git push` therefore does **not** deploy. After changing
`index.html`, deploy explicitly with the Vercel MCP `deploy_to_vercel` tool
targeting production.

**Every change gets deployed, without being asked.** Do not wait for a
"deploy it" instruction — finishing a change means the live site is updated.

**Do not hand me new links or files.** The address is always
https://loenberegner.vercel.app and it does not change. So:

- Do not send the `index.html` file as an attachment.
- Do not quote the per-deployment URL (the long
  `loenberegner-xxxxx-...vercel.app` one) — it is noise.

Just say it is deployed, and describe what changed.
