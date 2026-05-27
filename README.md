# Interactive CV Studio & Personal Letter Builder

An elegant, pure client-side HTML/CSS/JavaScript web application built to help job seekers draft, customize, and organize their CVs and Personal Letters concurrently. The application implements premium UX scanning theories (like the F-Pattern and Z-Pattern) natively within its document layouts.

## Key Features

- **Dual-Panel Workspace**: Draft your CV and Cover Letter side-by-side with automatic typography and theme synchronization.
- **F-Pattern Stem Layout**: CV structured with a left-margin column acting as an optical anchor so recruiters can scan vertically without getting lost.
- **Dynamic Theme Engine**: Select from pre-made aesthetic configurations (Navy, Modern Teal, Elegant Slate, Creative Berry) or pick your exact brand identity with native color pickers.
- **Interactive Drag-and-Drop Operations**: Reorder entire CV sections (Profile, Experience, Education, etc.) dynamically with immediate content persistence.
- **Rich Contextual Controls**: Easily clear individual elements, append new experience roles, or add expertise keywords via an adaptive tag/pill layout.
- **Cognitive Boundary Counter**: Live word tracking with visual danger thresholds (notifies you if your cover letter exceeds the optimal 300-word scanning cap).
- **In-Line Floating Text Formatting**: Highlight text elements anywhere within the editable regions to access a floating format menu for custom fonts, scaling sizes, or strong text treatments.
- **Optimized Print Styles (`@media print`)**: Hides editing bars, tooling wrappers, sidebars, and control items seamlessly when printing or exporting directly to PDF via standard browser capabilities (`Ctrl+P` / `Cmd+P`).
- **Zero Server Setup**: Leverages immediate `localStorage` synchronization for constant auto-saving.

## Architecture

- **Single-File Build**: Entirely self-contained in a single `.html` document containing all styling logic and JavaScript action handlers. No bundlers or build chains required.
- **Semantic DOM Injections**: Dynamically instantiates new sub-components for experiences, credentials, and tags using native component templating.

## Usage Instructions

1. Open the file `cv_maker_v14.html` inside any standard modern web browser.
2. Click directly on any text block to modify its contents in real-time.
3. Use the top configuration toolbar to toggle between structural Serif/Sans typography choices or to omit the profile image layout entirely.
4. Drag sections using the `⋮⋮` handles to reorder content categories.
5. Hit **PDF Export** or press your system print hotkey to generate a print-ready or digitally shareable CV document asset.
