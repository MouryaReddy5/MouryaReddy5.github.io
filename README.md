# Portfolio

Personal portfolio, live at https://mouryareddy5.github.io. Plain HTML/CSS/JS, no build step.

The featured project, [webgpu-llm-engine](https://github.com/MouryaReddy5/webgpu-llm-engine), and the apps live in their own repos and are linked from the home page:
[attention-lens](https://github.com/MouryaReddy5/attention-lens),
[optimizer-arena](https://github.com/MouryaReddy5/optimizer-arena),
[tinygpt-writer](https://github.com/MouryaReddy5/tinygpt-writer),
[grpo-playground](https://github.com/MouryaReddy5/grpo-playground).
`apps/` only holds redirects from the old URLs.

The visit counter in the footer uses the free [Abacus](https://abacus.jasoncameron.dev) counter API
(no cookies): `visits` counts page loads, `visitors` counts once per browser.

## Publish on GitHub Pages

1. Create a public repo named exactly `<your-username>.github.io` (here: `MouryaReddy5.github.io`).
2. Push this folder to it:
   ```bash
   git init && git add . && git commit -m "Portfolio" && git branch -M main
   git remote add origin https://github.com/MouryaReddy5/MouryaReddy5.github.io.git
   git push -u origin main
   ```
3. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `(root)`.
4. The site goes live at `https://mouryareddy5.github.io` within a minute or two.

## Run locally

Any static file server works, e.g. `python3 -m http.server` from this folder, then open http://localhost:8000.
