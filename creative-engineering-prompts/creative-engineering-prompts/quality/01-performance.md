# Module 24: Media and performance

## Claude Code task
Implement this module in the existing project, using CLAUDE.md and the master brief. Inspect existing components and content first; preserve completed behavior.

## Specific implementation
Use next/image sizes, local optimized AVIF/WebP, explicit dimensions; only hero preload. Video posters optimized, native lazy loading where appropriate, lazy-load canvas/globe. Avoid layout-shifting fonts; pause hidden animations. Target LCP <=2.5s, CLS <=0.1, INP <=200ms as field targets, not measured claims.

## Acceptance criteria
Record Lighthouse lab results and limitations; no invented performance numbers.

## Execution and handoff
Identify files to change; implement reusable typed components and necessary tests. Run relevant checks. Report changed paths, actual test results, remaining asset/configuration dependencies and any deviations. Do not use reference-site code or media without permission.
