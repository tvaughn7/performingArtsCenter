How to watch and build SCSS

This project compiles SCSS files in `scss/` into CSS files in `css/` using Dart Sass.

Quick setup (Windows PowerShell):

1. Install Node.js (if you don't have it): https://nodejs.org/
2. From the project root run:

```powershell
npm install
```

3. Start the watcher:

```powershell
npm run watch:sass
```

What the scripts do:
- `npm run watch:sass` — watches `scss/` and outputs compiled CSS into `css/` automatically on every change.
- `npm run build:sass` — builds compressed production CSS once.

Notes:
- The project `package.json` includes `sass` as a devDependency. `npm install` will install it locally.
- If you prefer a global install, run `npm install -g sass` and then use the same `sass --watch scss:css` command.
