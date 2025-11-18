# Human-AI Alignment Tutorial

This is a React-based tutorial for Human-AI Alignment concepts, built with Vite.

## Development

To run the development server:

```bash
npm run dev
```

## Building for Production

To build the project for production:

```bash
npm run build
```

## Deploying to GitHub Pages

### Prerequisites

1. Make sure you have the `gh-pages` package installed:
   ```bash
   npm install --save-dev gh-pages
   ```

   ```bash
   npm list gh-pages
   ```

2. Ensure your repository is connected to GitHub and you have the necessary permissions.

### Deployment Steps

1. **Build the project:**
   ```bash
   npm run build
   ```

2. **Deploy to GitHub Pages:**
   ```bash
   npm run deploy
   ```

   This will:
   - Build the project (via the `predeploy` script)
   - Deploy the contents of the `dist` folder to the `gh-pages` branch
   - Make your site available at: https://hai-alignment-course.github.io/tutorial/

### Configuration

The project is configured for GitHub Pages with:
- Base path: `/tutorial/` (set in `vite.config.js`)
- Homepage: `https://hai-alignment-course.github.io/tutorial/` (set in `package.json`)
- Build output directory: `dist` (Vite default)

### Troubleshooting

- If you get a 404 error, make sure GitHub Pages is enabled in your repository settings
- The site may take a few minutes to become available after deployment
- Check that the `gh-pages` branch was created in your repository

<!-- # React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project. -->



