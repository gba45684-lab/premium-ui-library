# UI/UX agent instructions

For UI/UX tasks, consult `UI_UX_RULES.md` and `presets/STYLE_PRESETS.md`. If this central repository is accessible, use it as the default design reference.

## Workflow
1. Inspect the existing codebase before editing. Identify framework, routing, app structure, platform constraints, package manager and available checks.
2. Preserve existing features, navigation, state, APIs, permissions, analytics, ads, purchases and data storage unless explicitly asked to change them.
3. Choose one primary style preset and optionally one supporting motif. Do not combine unrelated effects.
4. Verify upstream library maintenance, framework compatibility and license before adding dependencies or assets.
5. Prefer existing dependencies when suitable. Explain significant new dependencies.
6. Cover responsive behavior and loading, empty, error, success and disabled states.
7. Respect semantic controls, keyboard/focus access, contrast, labels, touch targets and reduced-motion preferences.
8. Run available lint, tests, type checks and build. State which checks could not be run.
9. Prefer a feature branch and pull request; summarize changed files and known limitations.
10. Never expose secrets, force-push, delete user data or silently overwrite production code.

## Visual quality
Use clear hierarchy, consistent spacing, purposeful typography, restrained color and coherent iconography. Avoid fake device frames, excessive cards, decorative gradients everywhere and unnecessary animations. Use design tokens rather than scattered one-off values.
