# AGENTS.md

Instructions for AI coding agents (Hermes Autopilot reads this automatically).

## Project
Model Viewer is a web‑based 3D model viewer built with PlayCanvas, allowing developers and designers to load, inspect, and interact with GLB/FBX assets directly in the browser.

## Commands
- Install: "none"
- Lint: "none"
- Test: "none"
All three must pass before a commit is pushed.

## Layout
- `Assets/` — source assets, scripts, and shaders for the viewer
- `docs/` — documentation and spec template files
- `ProjectSettings/` — Unity/PlayCanvas project configuration files
- `Scenes/` — scene definition JSON files
- `Documents/` — additional data assets
- `thumbnails/` — generated thumbnail images for models

## Rules
- Implement only what the task and its spec ask for. No unrelated refactors.
- Every behaviour in the acceptance criteria gets a test.
- Never commit secrets, generated files or dependency folders.
- If the spec is ambiguous, stop and ask instead of guessing.
