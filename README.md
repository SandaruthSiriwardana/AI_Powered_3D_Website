# AI_Powered_3D_Website

### setup process
1. First install the latest version of Vite as the project template.
    ``` bash
    npm create vite@latest -- --template react app
    ```
2. Go to the app directry
    ```bash
    cd app
    ```
3. For 3D graphics.
    - three  - This is the Three.js library itself, which is a popular JavaScript library for 3D graphics.
    - @types/three: These are TypeScript type definitions for Three.js, which help with type checking and code completion in TypeScript projects.
    - @react-three/fiber: This is a library that provides React bindings for Three.js, allowing you to create interactive 3D scenes using React components.
    - @react-three/drei: This is a collection of useful components, hooks, and utilities for building 3D applications with React and Three.js. It simplifies common tasks and provides pre-built components for common use cases.
      
    ```bash 
    npm install three @types/three @react-three/fiber @react-three/drei math valtio react-color framer-motion
    ```
4. Install Tailwind CSS
    ```bash 
    npm install -D tailwindcss postcss autoprefixer
    ```
5. Tnitializes a Tailwind CSS 
    ```bash 
    npx tailwindcss init -p
    ```
6. Start the development server
    ```bash
    npm run dev
    ```
