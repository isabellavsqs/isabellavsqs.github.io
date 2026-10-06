---
name: Jekyll preview watcher
description: Prevent repeated rebuilds caused by Replit's in-workspace workflow logs.
---

On root-level Jekyll projects in Replit, `jekyll serve` can treat updates to `.local/state/workflow-logs` as source changes and repeatedly regenerate the site, even if that directory is not copied into `_site`.

**Why:** Replit stores live workflow output under `.local` inside the project root that Jekyll watches.

**How to apply:** Add `.local` to the Jekyll `exclude` list before restarting the workflow. Exclude `.agents` as well when it contains only workspace/agent metadata.
