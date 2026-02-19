# Vue PWA Basic

A modern Progressive Web Application built with Vue 3 and Vite, featuring offline-first capabilities and installable app functionality. This repo is ready for developing your first Vue 3 PWA application.

You can read more here:
[Learn more about setting up a Vue PWA with Vite](https://zlatan.dk/post/how-to-set-up-a-vuejs-progressive-web-app-pwa-with-vite/)


## Prerequisites

- Node.js 16.0 or higher
- npm or yarn

## Installation

1. Install dependencies:
```bash
npm install
```

## Development

Start the development server with hot module replacement:
```bash
npm run dev
```

The application will be available at `http://localhost:5173` (or another port if 5173 is in use).

## Production Build

Build the application for production:
```bash
npm run build
```

The optimized build output will be in the `dist/` directory, ready for deployment.

## Preview Production Build

Preview the production build locally:
```bash
npm run preview
```

## PWA Features

This project includes complete PWA support:

- **Service Worker** - Automatically handles caching and offline functionality
- **Web Manifest** - Enables installation as a standalone app
- **Icons** - Automatically generated PWA icons for various devices and platforms
- **Prompt-based Updates** - Users are prompted when a new version is available

### Install as App

On supported platforms, users can:
- Click the "Install app" button in the browser
- Use the browser menu to install the app
- Add to home screen on mobile devices

Once installed, the app can run offline using cached assets and the service worker.

## Project Structure

```
src/
  ├── App.vue              # Root component
  ├── main.js              # Application entry point
  ├── style.css            # Global styles
  ├── assets/              # Static assets
  └── components/          # Vue components
      ├── HelloWorld.vue
      └── PWABadge.vue     # PWA installation badge
```

## IDE Support

For the best development experience, use an IDE with Vue 3 support:
- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) extension
- [WebStorm](https://www.jetbrains.com/webstorm/)
- [Sublime Text](https://www.sublimetext.com/) + [Vue plugin](https://packagecontrol.io/packages/Vue%20Syntax%20Highlight)

## Learn More

- [Vue 3 Documentation](https://vuejs.org/)
- [Vite Documentation](https://vitejs.dev/)
- [Vite PWA Plugin](https://vite-pwa-org.netlify.app/)
- [Web App Manifest](https://developer.mozilla.org/en-US/docs/Web/Manifest)
- [Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
