# PR #1 onboarding wizard screenshots

Static assets referenced from a draft PR. Captured via headless Chromium against `pnpm dev` on macOS.

- `01-wizard-step1.png` — Wizard Step 1 (no behavior change in this PR; baseline reference).
- `02-wizard-step2-pretest-Test-and-next.png` — Step 2 before the env test has run. The Next button reads **"Test & next"** (label adapts to env-test state).
- `03-wizard-step2-postpass-Next.png` — Step 2 after the env probe passes. The button collapses to **"Next"**.
