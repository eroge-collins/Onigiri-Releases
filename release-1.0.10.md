## What's New

- Fixed Windows installer packaging so Axios and its complete runtime dependency tree are included correctly in the packaged application.
- Switched production dependency installation to npm for reliable Electron packaging of nested runtime dependencies.
- Rebuilt and validated the 1.0.10 Windows installer without the previous `MODULE_NOT_FOUND` startup errors.
- Preserved the existing update-data protection introduced in 1.0.6+ and the LTK-based injection workflow.
