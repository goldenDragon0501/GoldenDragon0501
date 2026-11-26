# Module 07: Living background and cursor

## Claude Code task
Implement this module in the existing project, using CLAUDE.md and the master brief. Inspect existing components and content first; preserve completed behavior.

## Specific implementation
Draw gold particles on canvas with DPR capped at 2, max 70 particles desktop and 25 mobile. Pointer trail 18 samples with decay, pointer-events none; animate transform/opacity, pause when hidden or offscreen. Disable custom cursor on touch, reduced motion and form controls.

## Acceptance criteria
Native pointer remains usable; no animation loops after unmount; static fallback.

## Execution and handoff
Identify files to change; implement reusable typed components and necessary tests. Run relevant checks. Report changed paths, actual test results, remaining asset/configuration dependencies and any deviations. Do not use reference-site code or media without permission.
