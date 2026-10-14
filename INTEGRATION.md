# Integrate this design system into an app repository

## Important distinction
This repository is the shared source of truth, but it does not automatically change other repositories just because it exists. Each target repository must reference it and include local agent instructions. Automatic coding requires an authorized coding agent or workflow.

## Recommended low-friction setup
1. In each app repository, add a root `AGENTS.md` based on `templates/repo-uiux-instructions.md`.
2. Link to this central repository and the relevant rules:
   - https://github.com/gba45684-lab/premium-ui-library
   - https://github.com/gba45684-lab/premium-ui-library/blob/main/UI_UX_RULES.md
   - https://github.com/gba45684-lab/premium-ui-library/blob/main/presets/STYLE_PRESETS.md
3. During a UI task, the coding agent should read these files, inspect the app framework, then select a compatible preset.
4. Copy or adapt tokens/components only after checking the target app's framework and existing styles.
5. Submit changes in a branch/pull request and run the app's own tests/build.

## Optional Git submodule
If you want a local copy of this repository inside an app repository, run:
```bash
git submodule add https://github.com/gba45684-lab/premium-ui-library.git design-system
git submodule update --init --recursive
```
Submodules require an explicit update when the central repository changes; they are not automatic live synchronization.

## Automation safety
- Never give a workflow broad write permissions unless required.
- Store tokens only in GitHub Actions secrets.
- Do not run an agent that rewrites production branches without review.
- Use pull requests, project-specific build checks and explicit permissions.
- A workflow can check quality; it cannot invent reliable redesigns without a configured coding agent and app context.
