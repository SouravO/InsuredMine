# Copilot Instructions for insuredmine

This project is a minimal static web app with the following structure:

- `index.html`: Main HTML entry point. No scripts or frameworks detected.
- `assets/styles.scss`: Main stylesheet (currently empty).
- `assets/_variables.scss`: SCSS variables file (currently empty).
- `assets/README.txt`: Reserved for asset documentation (currently empty).

## Key Patterns & Conventions

- **Styling**: Use SCSS for all styles. Place global variables in `_variables.scss` and import them into `styles.scss` if needed.
- **HTML**: All markup is in `index.html`. No templating, JavaScript, or build tools are present.
- **Assets**: Store all styles and related files in the `assets/` directory.
- **No Build System**: There are no build, test, or deployment scripts. All files are static and manually managed.
- **No External Dependencies**: No package managers, libraries, or frameworks are used.

## Developer Workflow

- Edit `index.html` for markup changes.
- Edit SCSS files in `assets/` for styling. Compile SCSS to CSS manually if needed (no automation detected).
- Add new assets (images, fonts, etc.) to the `assets/` directory.

## Project-Specific Advice for AI Agents

- Do not introduce frameworks, build tools, or package managers unless explicitly requested.
- Keep all code and assets in the existing directory structure.
- Use SCSS features for styling, but ensure compatibility with plain CSS if compiling manually.
- Document any new conventions or patterns in `assets/README.txt`.

## Example: Adding a New Color Variable

In `assets/_variables.scss`:

```scss
$primary-color: #3498db;
```

In `assets/styles.scss`:

```scss
@import "variables";
body {
  background: $primary-color;
}
```

---

For questions about expanding the project, clarify requirements before adding new technologies or workflows.
