---
name: verify-helium
description: Verify a separately built Helium developer browser with an owned profile; keep source/patch checks separate from native window behavior.
---

# Verify Helium

Read README.md, CONTRIBUTING.md, repository AGENTS.md and the feature index.
This repository owns shared Chromium patches and resources. Platform packaging
and build commands belong to the matching platform repository. Do not infer a
working browser from a patch applying or from this source checkout.

Use an isolated checkout, an exact candidate revision, an owned developer
profile and a separately authorized platform build. Record the Chromium/Helium
versions, patch series, platform revision, artifact identity and native operator.
Check active owners, available memory/disk and existing developer processes.
No native build or device change is authorized by this procedure audit.

Require the exact developer browser to launch with its owned profile before
journeys. Use the platform's documented build/runtime controls and explicit
resource limits. Browser-tab automation cannot prove OS window dragging,
permission behavior or native frame hit testing.

Run selected feature extensions serially. Retain redacted captures under ignored
`.agents/artifacts/`. After a surprising result, recheck the artifact/profile,
reset only owned state and retry once. Stop only the developer process and
remove only its owned profile after retaining evidence. Keep the daily browser,
settings, credentials and upstream repositories unchanged.

Report source review, patch application, build, tests and native product journeys
separately. Publish task-authorized documentation only to Max's fork; this task
provides no authority to submit to imputnet repositories.
