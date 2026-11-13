# AI Passive Income with Microstock — Lepak Tech 2.0

Self-contained HTML slide deck (10 slides, 1920×1080), served by nginx in Docker.

## Controls
- `→` / `Space` / click: next slide · `←`: previous · `F`: fullscreen
- Jump to a slide with `#n` in the URL, e.g. `/#6`

## Run locally
```bash
docker compose up -d --build
# open http://localhost:8080
```

## Deploy with Easypanel
1. Create a new **App** service.
2. Source: **GitHub** → `digitalscapemy/slide-microstock-lepak-tech-2.0`, branch `main`.
3. Build: **Dockerfile** (path `Dockerfile`).
4. Domains: add your domain, set the proxy port to **80**.
5. Deploy. Health check endpoint: `/healthz`.
