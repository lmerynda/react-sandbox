# React sandbox

Uses React, TypeScript, Vite and Vitest. Use Node.js 24.15 or later within the
24.x release line (recommended), 22.22.2 or later within 22.x, or Node.js 26+.
The development container supplies Node.js 24.21.0.

Run `npm ci`, then:

- `npm start`: development server at http://localhost:5173.
- `npm test`: run the DOM component tests once.
- `npm run test:watch`: run tests in watch mode.
- `npm run build`: type-check and create the production site in `build/`.
- `npm run preview`: serve the production build locally.

The maintained Vite/Vitest tools replace Create React App and its obsolete
dependency chain. Web Vitals uses INP in place of the retired FID metric.
