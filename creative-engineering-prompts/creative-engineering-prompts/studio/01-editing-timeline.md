# Module 14: Motion editing console

## Claude Code task
Implement this module in the existing project, using CLAUDE.md and the master brief. Inspect existing components and content first; preserve completed behavior.

## Specific implementation
Use real HTMLVideoElement with currentTime, duration, loadedmetadata, timeupdate and ended. Draw timeline with 3 labeled conceptual tracks; seeking via range input and pointer; display mm:ss and progress. Do not pretend to edit source footage.

## Acceptance criteria
Seek clamped to duration; controls work before/after metadata; playback failure shown; captions when supplied.

## Execution and handoff
Identify files to change; implement reusable typed components and necessary tests. Run relevant checks. Report changed paths, actual test results, remaining asset/configuration dependencies and any deviations. Do not use reference-site code or media without permission.
