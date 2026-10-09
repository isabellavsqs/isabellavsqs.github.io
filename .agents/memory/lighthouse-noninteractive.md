---
name: Lighthouse noninteractive runs
description: Avoid the anonymous error-reporting prompt crash in shell-based Lighthouse runs.
---

In this Replit environment, Lighthouse can prompt for anonymous error reporting on its first CLI run. Without an interactive terminal, that prompt can fail with `ERR_USE_AFTER_CLOSE`.

**Why:** Shell checks run without a TTY or open stdin.

**How to apply:** Pass `--no-enable-error-reporting` to Lighthouse CLI runs.
