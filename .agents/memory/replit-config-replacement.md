---
name: Replit config replacement
description: The validated replacement flow for `.replit` when direct edits are blocked.
---

When Replit rejects direct `.replit` edits, stage the complete TOML in a temporary workspace file and call `verifyAndReplaceDotReplit` with its absolute path. Remove the temporary file after success.

**Why:** Replit's safeguard rejected direct patching in this workspace, but accepted the validated replacement.

**How to apply:** Use this flow when changing `.replit`; do not work around the validator with direct patching or shell edits.
