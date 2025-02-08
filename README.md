# Vite React Redux Template 🚀

This template provides a **fast and modern** React starter using **Vite, Redux Toolkit, and React Router**, featuring **HMR (Hot Module Replacement)** and **ESLint rules**.

## ✨ Features

- ⚡ **Vite** - Lightning-fast development experience
- ⚛ **React 19** - Latest version of React
- 🏛 **Redux Toolkit** - Simplified state management
- 🌍 **React Router** - Easy navigation between pages
- 📦 **ESLint & Prettier** - Code quality and formatting
- 🚀 **HMR (Hot Module Replacement)** - Instant UI updates during development

## 📌 Official Plugins

This template supports two React plugins for **Fast Refresh**:

| Plugin                                                                                                          | Transpiler                      | Recommended For                           |
| --------------------------------------------------------------------------------------------------------------- | ------------------------------- | ----------------------------------------- |
| [`@vitejs/plugin-react`](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) | **Babel**                       | Feature-rich, supports legacy code        |
| [`@vitejs/plugin-react-swc`](https://github.com/vitejs/vite-plugin-react-swc)                                   | **SWC** (10x faster than Babel) | Best for **performance-focused** projects |

## Getting Started

To create a new project using this template, run:

```sh
npx degit adriancretu03/vite-redux-template my-project
cd my-project
npm install
```

or using Yarn:

```sh
npx degit adriancretu03/vite-redux-template my-project
cd my-project
yarn install
```

## Development

Start the development server:

```sh
npm run dev
```

or

```sh
yarn dev
```

## Build for Production

To build the project for production:

```sh
npm run build
```

or

```sh
yarn build
```

## Folder Structure

```
my-project/
├── public/           # Static public files
├── src/
│   ├── app/          # Redux store configuration
│   ├── assets/       # Static assets
│   ├── components/   # Reusable components
│   ├── features/     # Redux slices and async thunks
│   ├── hooks/        # Custom React hooks
│   ├── pages/        # Page components
│   ├── routes/       # Application routes
│   ├── main.jsx      # Entry point
│   └── App.jsx       # Main application component
├── .gitignore        # Ignore files for Git
├── .prettierrc       # Prettier configuration
├── eslint.config.js  # ESLint configuration
├── index.html        # HTML entry file
├── LICENSE           # MIT license
├── package.json      # Dependencies and scripts
├── README.md         # Project documentation
└── vite.config.js    # Vite configuration
```

## Contributing

Feel free to submit issues or pull requests to improve this template!

## License

This project is licensed under the MIT License.
