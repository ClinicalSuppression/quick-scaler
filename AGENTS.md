# Agent Guidelines & Workflow Rules

## 1. Commits and Releases
- Make focused, reviewable commits after appropriate verification; avoid committing unrelated user changes.
- Push verified work directly to the default branch by default. Use a feature branch or pull request when requested or when separate review is warranted.
- Reserve version tags and GitHub releases for major, stable release milestones.

## 2. Standardized Release Assets
Every major stable release must include:
- **Source Zip**: A normalized source archive (`<repo-name>-vX.Y.Z-src.zip`).
- **Terminal Installation Instructions**: Clear instructions in `README.md` for terminal/CLI installation (e.g., `git clone` into plugin directories).
- **Executables (`.exe`)**: If the app compiles or builds an `.exe`, include both:
  1. A portable executable package.
  2. An installation candidate (`.exe` installer / setup executable).
  - *Note*: If a portable version is unfeasible, notify the user and ask for direction before publishing.
