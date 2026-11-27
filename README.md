# Portfolio

Personal portfolio plus four in-browser ML apps. Plain HTML/CSS/JS, no build step, ready for GitHub Pages.

```
index.html                 portfolio home
assets/site.css, theme.js  shared styles + light/dark toggle
apps/attention-lens/       multi-head attention with sinusoidal / RoPE / ALiBi
apps/optimizer-arena/      SGD, Momentum, RMSProp, Adam, Muon on 2D loss landscapes
apps/tinygpt/              char-level GPT trained in the browser (TensorFlow.js, WebGL)
apps/grpo/                 GRPO vs REINFORCE on a toy arithmetic task
```

## Before publishing

Search for `TODO` in `index.html` and fill in: your name, title, bio, LinkedIn, email,
experience/education, and drop a `resume.pdf` in the repo root.

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
