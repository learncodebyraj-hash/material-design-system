# Material Design System

A lightweight, pure CSS implementation of **Google's Material Design 3** tokens. This repository provides the foundational variables (CSS Custom Properties) needed to build a Material Design 3 application without heavy framework dependencies.

## Features

- **Standard Tokens:** Includes all baseline M3 Reference (`--md-ref-palette-*`) and System (`--md-sys-color-*`) tokens.
- **Dark Mode Support:** Built-in `@media (prefers-color-scheme: dark)` overrides for automatic theme switching.
- **Typography & Elevation:** Includes standard type scale and shadow tokens.
- **No Dependencies:** Pure CSS variables.

## Usage

1.  **Import the tokens:**
    Include `material-tokens.css` in your project.

    ```css
    @import 'material-tokens.css';
    ```

2.  **Use variables in your CSS:**
    Apply the system tokens to your elements.

    ```css
    body {
        background-color: var(--md-sys-color-background);
        color: var(--md-sys-color-on-background);
    }

    .card {
        background-color: var(--md-sys-color-surface);
        color: var(--md-sys-color-on-surface);
        border: 1px solid var(--md-sys-color-outline);
    }

    .primary-button {
        background-color: var(--md-sys-color-primary);
        color: var(--md-sys-color-on-primary);
    }
    ```

## Demo

Open `index.html` in your browser to see a visual verification of the tokens, including palettes, typography, and elevation samples.
