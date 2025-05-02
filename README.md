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