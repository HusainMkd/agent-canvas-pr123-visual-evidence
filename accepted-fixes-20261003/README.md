# Accepted auth / onboarding / theme fixes

Actual merged AgentCanvas/controller/tldraw rendered in Chromium at 1280×900.
Clerk, Convex source data, theme controls, and runner discovery are explicit
runtime fixtures (banner visible). No live app authentication or model inference
is claimed by these screenshots/GIF.

- `stable-light.png` / `stable-dark.png`: same rectangle and live editor across
  light→dark. `verification.json` records unchanged editor mount/unmount counts.
- `automatic-readiness.png`: external runner auto-probes, pairing is supplied
  in memory, connected inventory/model/variant controls appear automatically.
- `stable-theme-readiness.gif`: continuous 11.5-second browser recording of the
  above, scaled to 960×675 at 6 fps; no recreated frames.
- Original WebM retained for provenance.

The original reported persistent blank screen remains unconfirmed. The proven
theme-driven editor teardown and clipped controls are fixed. Template-free auth
still requires coordinated matching Convex customJwt issuer/JWKS deployment;
see `docs/agent-canvas-auth.md`. No account/env/production mutation occurred.
