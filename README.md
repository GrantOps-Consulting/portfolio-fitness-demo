# portfolio-fitness-demo

Single-file static portfolio demo for GrantOps Consulting's homepage `ProjectsGrid`. Brand: **BOXWORKS Athletic Co.** — fictional independent boxing &amp; strength gym in Bridgeton, Glasgow.

Deployed to `fitness-demo.grantopsconsulting.com` via GitHub Actions OIDC on push to `main`. Infrastructure (S3 + Cloudflare DNS) lives in `GrantOps-Consulting/grantops-web-infra` under client slug `portfolio-fitness-demo`.

## Notes

- `<meta name="robots" content="noindex, nofollow">` — only intended path is the curated link from grantopsconsulting.com.
- Footer carries: *Portfolio demo by GrantOps Consulting — no real business sits at this address. View our work at [grantopsconsulting.com](https://grantopsconsulting.com/).*
- No build step. `index.html` ships exactly as committed.
