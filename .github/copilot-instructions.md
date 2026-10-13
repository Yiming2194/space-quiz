# Project Guidelines: Space Exploration Quiz

## Architecture & Tech Stack
- **Single File**: Self-contained `index.html` containing all HTML, CSS, and vanilla JavaScript.
- **Zero Dependencies**: No build steps, bundlers, package managers, or external runtime libraries/CDNs.
- **Standalone Execution**: Runs directly via `file://` or any static HTTP server.

## Design & UI Standards
- **Layout**: Centered narrow column (max-width: 480px) optimized for desktop and mobile viewports.
- **Typography**: Clean system sans-serif stack, body font size 14–16px.
- **Theming**: Automatic light and dark theme support via CSS custom properties and `prefers-color-scheme`.
- **Aesthetic**: Polished mission-control inspired telemetry interface with clear visual feedback states.

## Interaction & Accessibility
- **Keyboard Navigation**: Full keyboard operability (A–D / 1–4 to select options, Enter to advance/restart).
- **Reduced Motion**: Respect `prefers-reduced-motion` for background starfield, confetti, and shake/pop animations.
- **Feedback & ARIA**: Accessible live regions, focus indicators (`:focus-visible`), and semantic markup.
