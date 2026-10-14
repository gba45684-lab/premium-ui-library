# Premium UI Library

A reusable, framework-aware design system reference for polished UI/UX across current and future apps.

## Purpose
Centralize design principles, style presets, tokens, reusable patterns and implementation rules. This repository is a reference library—not a universal drop-in package. Select libraries compatible with each app's actual framework and verify their current licenses before use.

## Style presets
See [presets/STYLE_PRESETS.md](presets/STYLE_PRESETS.md): Glassmorphism, Liquid Glass-inspired UI, Bento Grid, Premium Minimalism, Neumorphism, Aurora Gradients, Material Design 3, Dark Luxury, Neobrutalism, Claymorphism, Editorial/Swiss, Neon/Cyberpunk and restrained 3D/depth.

## Using this library
1. Inspect the target app's framework, routes, dependencies, design and tests.
2. Choose one primary preset and at most one supporting visual motif.
3. Preserve existing product features, data contracts and navigation.
4. Adapt components to the app's stack; don't force a React library into plain HTML or native UI.
5. Run available checks and open a pull request with a clear summary.

## Start here
- [AGENTS.md](AGENTS.md): coding-agent instructions
- [UI_UX_RULES.md](UI_UX_RULES.md): quality and accessibility rules
- [Style presets](presets/STYLE_PRESETS.md)
- [Open-source resources](presets/OPEN_SOURCE_RESOURCES.md)
- [Design review checklist](templates/design-review-checklist.md)
- [Starter tokens](tokens/tokens.css)

## Important
GitHub Actions alone will not redesign an app. Automated implementation requires a separately configured coding agent, scoped credentials and review. Never place API keys or tokens in source files.
