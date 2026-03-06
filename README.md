# Pokemon App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

The project uses **Yarn** as the package manager, managed via **Corepack**.

---

# Setup

Enable Corepack and activate Yarn:

```
corepack enable
corepack prepare yarn@stable --activate
```

Install dependencies:

```
yarn install
```

Start the development server:

```
yarn start
```

The application will be available at:

http://localhost:3000

---

# Available Scripts

### Start development server

```
yarn start
```

Runs the app in development mode.
The page reloads automatically when files change.

---

### Run tests

```
yarn test
```

Runs the test runner in watch mode.

---

### Build for production

```
yarn build
```

Creates an optimized production build in the `build` folder.

---

# Reset Dependencies

If dependencies become corrupted or the project stops compiling correctly, you can perform a clean reset:

```
rm -rf node_modules yarn.lock build
yarn cache clean
yarn install
yarn start
```

---

# Eject

```
yarn eject
```

This exposes the underlying build configuration (Webpack, Babel, ESLint).
This operation is **irreversible**.

---

# Learn More

Create React App documentation
https://create-react-app.dev/

React documentation
https://react.dev/
