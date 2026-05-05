# Archive Status

This public project is closed for active development as of 2026-05-05.

Purpose:
- Preserve the research/prototype state.
- Keep the project safe to reopen in a lab environment later.
- Avoid publishing live secrets or operational credentials.

Reopen checklist:
1. Clone the repository into a clean lab workspace.
2. Review current dependencies and browser/API compatibility.
3. Create fresh environment variables or deployment credentials outside git.
4. Run the app locally and smoke-test the primary workflow.
5. Record any resumed work in a new branch before changing `main`.

Security notes:
- Do not commit `.env`, provider keys, deploy tokens, or private data.
- Rotate any credential that was ever pasted into local scripts before reuse.
