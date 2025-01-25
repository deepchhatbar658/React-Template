# React TypeScript Template

This template provides a modern, robust starting point for building scalable React applications with TypeScript, Vite, and Material UI. It integrates essential libraries and tools to ensure a productive workflow and maintain high code quality.

---

## Features

### 1. **Core Stack**

- **React 19**: Built with the latest version of React for hooks and concurrent rendering.
- **TypeScript**: Adds static typing for better code quality and maintainability.

### 2. **Build and Development**

- **Vite**: Lightning-fast build and development environment with powerful plugin support.

### 3. **State Management**

- **@tanstack/react-query**: Efficient server-state management and caching.

### 4. **UI and Styling**

- **MUI (Material UI)**: Fully-featured, customizable UI components.
- **Emotion**: CSS-in-JS library for dynamic and responsive styling.

### 5. **Form Handling**

- **Formik**: Simplifies form management.
- **Yup**: Provides schema-based form validation.

### 6. **Routing**

- **React Router**: Easy navigation and route management.

### 7. **Reusable Components**

- **React Icons**: Easy-to-use icon library.
- **mui-one-time-password-input**: Specialized OTP input field.

### 8. **Linting and Code Quality**

- **ESLint**: Ensures clean and error-free code.
- **Plugins**: Includes `eslint-plugin-react-hooks` for hooks best practices.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repository-name.git
   ```

2. Navigate to the project folder:

   ```bash
   cd your-repository-name
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

---

## Scripts

- `dev`: Start the development server.
  ```bash
  npm run dev
  ```
- `build`: Compile TypeScript and build the app for production.
  ```bash
  npm run build
  ```
- `lint`: Run ESLint to maintain code quality.
  ```bash
  npm run lint
  ```
- `preview`: Preview the production build locally.
  ```bash
  npm run preview
  ```

---

## Folder Structure

```
├── src
│   ├── components  # Reusable React components
│   ├── pages       # Application pages
│   ├── styles      # Global and component-specific styles
│   ├── utils       # Utility functions and helpers
├── public          # Static files
├── package.json    # Project metadata and dependencies
├── tsconfig.json   # TypeScript configuration
└── vite.config.ts  # Vite configuration
```

---

## Dependencies

### **Core Dependencies**

- `react`: ^19.0.0
- `react-dom`: ^19.0.0
- `@mui/material`: ^6.4.1
- `@emotion/react`: ^11.14.0
- `@emotion/styled`: ^11.14.0
- `@tanstack/react-query`: ^5.64.2
- `formik`: ^2.4.6
- `yup`: ^1.6.1
- `react-router`: ^7.1.3
- `mui-one-time-password-input`: ^3.0.2

### **Dev Dependencies**

- `vite`: ^6.0.11
- `typescript`: \~5.7.3
- `eslint`: ^9.19.0
- `@vitejs/plugin-react`: ^4.3.4
- `@types/react`: ^19.0.8
- `@types/react-dom`: ^19.0.3

---

## Contribution

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch.
4. Submit a pull request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Support

For issues or questions, please open an issue on [GitHub](https://github.com/your-repository-name/issues).

