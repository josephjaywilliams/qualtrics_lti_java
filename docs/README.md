# One Minute

A no-install web app that gives you one small action you can do in 60 seconds, for movement, eating, or mental well-being.

It is built on the design principles and prompts from Hassanzadeh et al. (2026), [Designing for the Moment: How One-Minute Interventions Fit or Falter Across Domains](https://arxiv.org/abs/2605.29051):

- **Ultra-brief, immediate actions**: each prompt is one thing to do right now.
- **Low scaffolding**: no account, no setup; a guided 60-second timer replaces the study's optional videos.
- **Clear success state**: a 60-second dial and a Done button.
- **Reward-focused framing**: every prompt says why it helps.

It also acts on the paper's findings:

- **Four frictions** (timing, place, resources, mental effort): "Anything in the way?" filters and "Not now" reasons steer away from prompts that don't fit the moment.
- **Co-authorship**: "Rewrite in my words" saves your own version of a prompt and shows it from then on.
- **Two flows**: "Just do it" (immediate action) and "Check in first" (reflection-first), as in the study.
- **Daily nudge**: a 14-day Google Calendar reminder in a morning, afternoon, or evening window.

Prompts marked "From the study" are the 12 from the paper's Table 3; the others follow the same principles. All data stays in the browser's localStorage.

The whole app is `index.html` with no build step. Open it in a browser, or serve this folder with GitHub Pages (see `.github/workflows/pages.yml`).
