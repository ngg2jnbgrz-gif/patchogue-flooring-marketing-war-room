# Patchogue Flooring — Marketing Analytics War Room

Tron/HUD analytics app for the social content trial. Live via GitHub Pages.

## Regenerate

```bash
cd ~/workspace/patchogue-flooring-content && python3 build_analytics_site.py
cd ~/workspace/mktg-war-room-site-repo && git add -A && git commit -m "refresh" && git push
```

Pages redeploys automatically on push to `main`.
Post metrics persist in the browser via localStorage (per week).
