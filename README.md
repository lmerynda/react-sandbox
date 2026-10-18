# React sandbox

Uses React, TypeScript, Vite and Vitest. Requires Node.js 22.12 or later.

Run `npm ci`, then:

- `npm start`: development server at http://localhost:5173.
- `npm test`: run the DOM component tests once.
- `npm run test:watch`: run tests in watch mode.
- `npm run build`: type-check and create the production site in `build/`.
- `npm run preview`: serve the production build locally.

The maintained Vite/Vitest tools replace Create React App and its obsolete
dependency chain. Web Vitals uses INP in place of the retired FID metric.
