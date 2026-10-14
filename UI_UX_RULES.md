# UI/UX rules

## Design principles
- Premium, modern, compact, professional and responsive.
- Let hierarchy, spacing, alignment and typography lead; use effects as supporting details.
- Define semantic tokens for color, typography, spacing, radius, elevation, motion and breakpoints.
- Include useful loading, empty, error, success and disabled states.
- Check narrow mobile, large mobile, tablet and desktop as relevant.
- Preserve platform conventions across web, Capacitor, Android, iOS and desktop.
- Aim for accessible contrast, visible focus, semantic controls, labels, keyboard/touch support and reduced motion.

## Choosing presets
- Glassmorphism: selective overlays, floating panels and hero surfaces; keep text legible and provide a solid fallback.
- Liquid Glass-inspired: original, restrained translucent layers; do not copy proprietary assets or imply official affiliation.
- Bento Grid: modular dashboards and feature summaries.
- Premium Minimalism: finance, productivity, resumes and document tools.
- Material Design 3: Android-first apps and familiar adaptive controls.
- Neumorphism: limited use only; avoid low contrast and ambiguous affordances.
- Aurora/Gradient: emphasis and hero areas, not every surface.
- Dark Luxury: deliberate premium dark themes with readable contrast.
- Neobrutalism/Modern Brutalism: bold, high-contrast products where suitable.
- Claymorphism: friendly consumer experiences.
- Editorial/Swiss: content-heavy, typographic experiences.
- Neon/Cyberpunk: sparingly, where the audience and brand support it.
- 3D/depth: only where it improves comprehension; consider performance and reduced motion.

## Glass safeguards
Use blur as enhancement, never as the only content separation. Keep sufficient surface opacity, avoid busy imagery behind text, and supply fallbacks where backdrop-filter is unsupported.

## Suggested semantic tokens
`--color-bg`, `--color-surface`, `--color-text`, `--color-muted`, `--color-primary`, `--color-accent`, `--color-border`, `--space-1..8`, `--radius-sm..xl`, `--shadow-sm..lg`, `--motion-fast`, `--motion-standard`, `--content-max`, `--page-gutter`.
