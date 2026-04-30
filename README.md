# Mobile UI/UX Workspace (Figma + VS Code)

This project is set up for **mobile UI/UX design and prototyping only**.

## What is ready

- Figma integration in VS Code (recommended extension)
- Design token system in `styles/tokens.css`
- Mobile app screen starter in `index.html` + `styles/main.css`
- Live preview support via Live Server

## Folder structure

- `index.html` - main prototype page
- `styles/tokens.css` - shared design tokens (colors, spacing, radius, typography)
- `styles/main.css` - component and layout styles
- `scripts/main.js` - tiny interaction script for prototype feel
- `.vscode/extensions.json` - recommended extensions
- `.vscode/settings.json` - workspace settings

## First run

1. Install **Live Server** extension if not installed.
2. Open `index.html`.
3. Right click > **Open with Live Server**.
4. Open browser mobile mode (or test on your phone).
5. Start designing in Figma and map styles into `styles/tokens.css`.

## Figma-to-code workflow

1. In Figma, define color, spacing, and text styles.
2. Mirror those values in `styles/tokens.css`.
3. Build mobile screens/components in `index.html`.
4. Keep visual rules centralized in `styles/main.css`.
5. Iterate quickly with Live Server on desktop and mobile.

## Optional local tools

For advanced component frameworks later, install Node.js LTS.
This starter does not require Node.js.
