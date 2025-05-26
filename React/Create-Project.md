# How to Create a React App

Follow these steps to create a new React application:

## 1. Install Node.js

Make sure you have [Node.js](https://nodejs.org/) installed on your system.

## 2. Check Node.js Version

Open your terminal and run:

```sh
node -v
```

This will display your installed Node.js version. React requires Node.js 14.0.0 or higher.

## 3. Install React (if not already installed)

If you don't have `create-react-app` installed, you can use `npx` (recommended), or install it globally:

```sh
npm install -g create-react-app
```

> **Tip:** Using `npx` (as shown in the next step) does not require a global install.

## 4. Create a New React App

Open your terminal and run:

```sh
npx create-react-app my-app
```

Replace `my-app` with your desired project name.

## 5. Start the Development Server

Navigate to your project folder and start the development server:

```sh
cd my-app
npm start
```

Your React app will open in your browser at [http://localhost:3000](http://localhost:3000).

## 6. Next Steps

- Edit files in the `src` directory to start building your app.
- Refer to the [React documentation](https://react.dev/) for more information.