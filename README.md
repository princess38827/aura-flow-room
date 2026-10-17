# Aura Flow Room — Four-agent workflow demo

A responsive, dependency-free interface for the Aura Flow Room concept. It uses the Nova, Lyra, Atlas, and Sage portraits as local assets and presents a dark, futuristic multi-agent workspace.

**Live demo:** https://princess38827.github.io/aura-flow-room/

## Run locally

From this folder, start a static server:

```sh
python3 -m http.server 4173 --bind 0.0.0.0
```

Then open `http://localhost:4173`.

## What you can try

- Switch between Balanced, Research lens, Strategy room, and Creative sprint flow presets.
- Toggle Lyra, Atlas, and Sage independently; Nova remains the coordinator.
- Load a task prompt preset, edit the brief, and run the local demo.
- Watch the routing, sequential specialist handoffs, run trace, and Nova synthesis update in the UI.
- Copy the review output or clear the run history.

## Important

This is an interactive **scripted demo**, not a model-backed chatbot. The displayed notes are preset examples; no AI model, external research, web search, connected service, or persistence is configured. Do not treat the sample output as verified advice or factual research.

## Deployment

The site is a static HTML app hosted by GitHub Pages from the repository's `main` branch root. Push changes to `main` to publish them; no build step is needed.

## Files

- `index.html` — complete UI, styles, and interactions
- `assets/nova.jpg`, `assets/lyra.jpg`, `assets/atlas.jpg`, `assets/sage.jpg` — persona portraits
