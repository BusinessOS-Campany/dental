# dental

Business OS system repository. This single repository serves both trees:

- `real/` â€” the customer-facing system, deployed into `system/dental`.
- `demo/` â€” the public demo, deployed into `demo-systems/dental`.

A push to the production branch updates BOTH, as configured in the platform's
`config/deploy.json`. See the platform's `docs/DEPLOY-GIT.md`.
