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

-------------------------------------------------------------------------------------------------------------

## to correctly setup server folder

1. firstly close all the currently opening files regarding to the "app" folder
2. Then create a folder name "server"
3. open the terminal and press "ctrl+c" to stop the server
4. Go to the app directry
    ```bash
    cd ..
    cd .\server\     #to go to the file directly
    ```
5. To install files regarding to the package jason
    ```bash
   npm init -y
    ```
6. to install dependancies
    ```bash
    npm install cloudinary cors dotenv express mongoose nodemon openai
    ```

7. to start the server
    ```bash
    npm start
    ```

## To create a OPENAI API KEY
1. Go to the website https://platform.openai.com/account/api-keys
2. Create a new API key and copy it
3. Create a file name ".env" in the server folder and paste the API key in it