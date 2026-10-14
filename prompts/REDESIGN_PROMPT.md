# Reusable UI/UX redesign prompt

Act as a senior product designer and frontend/mobile engineer. First inspect the existing repository and identify the actual stack, product purpose, current flows, components, dependencies and available tests. Consult the central design system at https://github.com/gba45684-lab/premium-ui-library, especially UI_UX_RULES.md and presets/STYLE_PRESETS.md.

Then:
1. Recommend one primary preset and at most one supporting motif, based on this app's audience and platform.
2. Briefly map existing screens and functionality that must be preserved.
3. Implement a coherent, premium, responsive design using shared tokens and reusable components appropriate to the current stack.
4. Do not add libraries or copy assets until their compatibility and license are checked.
5. Preserve all business logic, routes, data contracts, storage, permissions, ads and purchases.
6. Handle loading, empty, error, success, disabled, focus and reduced-motion states.
7. Run available lint, type checks, tests and build. Report results truthfully.
8. Summarize the files changed and any limitations. Prefer a reviewable pull request over direct production changes.

Avoid generic template styling, fake device frames, excessive glass/blur, gradients on every surface, gratuitous animation and inaccessible low-contrast controls. Do not claim automatic deployment or successful tests unless verified.
