# coding-agent-demo

A modern web application built with the latest versions of Vite, React, and Node.js.

## 🚀 Tech Stack

- **Vite**: 7.2.2 - Next Generation Frontend Tooling
- **React**: 19.2.0 - A JavaScript library for building user interfaces
- **Node.js**: v20.19.5 - JavaScript runtime

## 📦 Getting Started

### Prerequisites

- Node.js v20.x or higher
- npm v10.x or higher

### Installation

```bash
# Install dependencies
npm install
```

### Development

```bash
# Start development server
npm run dev
```

The application will be available at `http://localhost:5173/`

### Build

```bash
# Build for production
npm run build
```

### Preview Production Build

```bash
# Preview the production build locally
npm run preview
```

### Lint

```bash
# Run ESLint
npm run lint
```

## 📝 About This Template

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
