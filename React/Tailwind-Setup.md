# How to Add Tailwind CSS to a React App

Follow these steps to set up Tailwind CSS in your React application.

## 1. Create a React App

If you haven't already created a React app, follow the guide here: [How to Create a React App](./Create-Project.md)

## 2. Install Tailwind CSS

Open your terminal and run:

```sh
npm install tailwindcss @tailwindcss/cli
```

## 3. Create Tailwind Input File

Create a file named `input.css` inside your `src` folder and add the following line:

```css
@import "tailwindcss";
```

## 4. Build Tailwind CSS

You can build your Tailwind CSS file by running:

```sh
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

Alternatively, add a script to your `package.json` for easier usage:

```json
"scripts": {
  "dev": "npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch"
}
```

Then run:

```sh
npm run dev
```

## 5. Link Tailwind CSS in Your Project

In your `public/index.html` file, add the following line inside the `<head>` tag to include the generated CSS:

```html
<link href="../src/output.css" rel="stylesheet">
```

For a fallback, you can also add the Tailwind CDN:

```html
<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
```

---

Your React app is now set up with Tailwind CSS! You can start using Tailwind utility classes in your components.