To start the slide show:

- `pnpm install`
- `pnpm dev`
- visit <http://localhost:3030>

Edit the [slides.md](./slides.md) to see the changes.


```bash
npm install @slidev/types
npm i -D prettier prettier-plugin-slidev
npm install monaco-editor
npm install slidev-addon-tldraw
npm i -D playwright-chromium
slidev export --format pptx
```

**Build and deploy**
```bash
slidev build

# preview the build
npx vite preview
```

-–-

### Slidev Addon Python Runner (`slidev-addon-python-runner` add in future)

# Optional configuration for this runner
python:
  # Install packages from PyPI. Default: []
  installs: ["cowsay"]

  # Code executed to set up the environment. Default: ""
  prelude: |
    GREETING_FROM_PRELUDE = "Hello, Slidev!"

  # Automatically load the imported builtin packages. Default: true
  loadPackagesFromImports: true

  # Disable annoying warning from `pandas`. Default: true
  suppressDeprecationWarnings: true

  # Always reload the Python environment when the code changes. Default: false
  alwaysReload: false

  # Options passed to `loadPyodide`. Default: {}
  loadPyodideOptions: {}