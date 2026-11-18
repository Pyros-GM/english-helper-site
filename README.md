# English Helper site

Served by GitHub Pages at https://pyros-gm.github.io/english-helper-site/

- `privacy.html` – the app's privacy policy (English + 中文). Linked from Settings and from Play Console > App content > Privacy policy.
- `version.json` – read by the app at start-up to tell players when a new version is on Google Play.
  - `latest_code` / `latest_version`: newest release (raise only once the Play rollout is at 100%)
  - `min_code`: versions below this must update (card can't be closed); 0 = never force
  - `message` / `message_zh`: optional one-line teaser shown with the banner
