# User Taste

## Communication
- Writes to the assistant in Persian (Farsi); respond in Persian. Confidence: 0.8

## Workflow
- Expects fixes to be verified before hand-off: rebuild the project (use a clean rebuild when new source files are added, since incremental builds can skip them), and smoke-test or add a quick unit test for tricky logic (e.g., diff vendored/generated tables against the upstream source). Confidence: 0.7
- Verifies fixes manually on real hardware (macVNC server on the Mac, vncviewer from a Raspberry Pi); close out with concrete rebuild/run commands the user can run themselves. Confidence: 0.7
