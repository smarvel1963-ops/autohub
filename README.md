# Auto Hub
Save path: C:/MarvelApps/autohub/README.md

Live: https://smarvel1963-ops.github.io/autohub/ - app #5 of the Marvel Corp Hub family (Scott 2026-10-14: logo + Auto Hub
plan: C:\MarvelDesktop\docs\AUTO_HUB_PLAN_FROM_OUTSIDE_CHAT_2026-10-14.md).

This repo is Auto Hub's OWN shell: `index.html`, `manifest.json`, icons and `sw.js`. The app itself is the shared Hub
engine in the Day Hub repo run with `window.DH_MODE = "auto"` plus `auto.js` (garage, maintenance, fuel, recalls).

- Own data on the phone (`autohub.v1`).
- Release 1: My Garage (VIN lookup via NHTSA vPIC), Smart Maintenance (miles or months), Fuel / MPG, Recalls (NHTSA).
- Auto Hub Pro $2.99/mo (30-day free trial) = the AUTO_PASS switch in ../dayhub/features.js, OFF until the Whop product.
- Tests + release steps: the Day Hub repo (`python tests/run_tests.py`).
