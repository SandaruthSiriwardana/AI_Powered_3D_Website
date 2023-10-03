# AI-Powered 3D Website

Welcome to the AI-Powered 3D Website project! This project aims to create an interactive 3D website using React, Three.js, and other essential libraries. It also integrates OpenAI's capabilities for added functionality.

<table align="center">
  <tr>
    <td align="center"><img src="https://github.com/SandaruthSiriwardana/AI_Powered_3D_Website/blob/2384a32c46f017a2654c3360441c26402a34314f/app/img/home.png" width="350" alt="Image 1"></td>
    <td align="center"><img src="https://github.com/SandaruthSiriwardana/AI_Powered_3D_Website/blob/2384a32c46f017a2654c3360441c26402a34314f/app/img/playground%20.png" width="350" alt="Image 2"></td>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/SandaruthSiriwardana/AI_Powered_3D_Website/blob/2384a32c46f017a2654c3360441c26402a34314f/app/img/add%20image.png" width="350" alt="Image 3"></td>
    <td align="center"><img src="https://github.com/SandaruthSiriwardana/AI_Powered_3D_Website/blob/2384a32c46f017a2654c3360441c26402a34314f/app/img/ai.png" width="350" alt="Image 4"></td>
  </tr>
</table>



## Table of Contents

- [Setup Process](#setup-process)
  - [Step 1: Install Vite](#step-1-install-vite)
  - [Step 2: Navigate to the App Directory](#step-2-navigate-to-the-app-directory)
  - [Step 3: Install 3D Graphics Dependencies](#step-3-install-3d-graphics-dependencies)
  - [Step 4: Install Tailwind CSS](#step-4-install-tailwind-css)
  - [Step 5: Initialize Tailwind CSS](#step-5-initialize-tailwind-css)
  - [Step 6: Start the Development Server](#step-6-start-the-development-server)
- [Setting Up the Server Folder](#setting-up-the-server-folder)
  - [Step 1: Close Existing Files](#step-1-close-existing-files)
  - [Step 2: Create a Server Folder](#step-2-create-a-server-folder)
  - [Step 3: Navigate to the Server Folder](#step-3-navigate-to-the-server-folder)
  - [Step 4: Initialize a Node.js Package](#step-4-initialize-a-nodejs-package)
  - [Step 5: Install Server Dependencies](#step-5-install-server-dependencies)
  - [Step 6: Start the Server](#step-6-start-the-server)
- [Creating an OpenAI API Key](#creating-an-openai-api-key)
- [Acknowledgments](#acknowledgments)

## Setup Process

### Step 1: Install Vite

First, install the latest version of Vite as the project template. Run the following command:

```bash
npm create vite@latest -- --template react app
```
### Step 2: Navigate to the App Directory
Go to the app directory
```bash
cd app
```
### Step 3: Install 3D Graphics Dependencies
For 3D graphics, we need to install the following libraries and dependencies:

- Three.js: A popular JavaScript library for 3D graphics.
- @types/three: TypeScript type definitions for Three.js.
- @react-three/fiber: React bindings for Three.js.
- @react-three/drei: A collection of components, hooks, and utilities for building 3D applications with React and Three.js.
- math, valtio, react-color, framer-motion: Additional libraries and utilities.

Run the following command to install these dependencies:
```bash
npm install three @types/three @react-three/fiber @react-three/drei math valtio react-color framer-motion
```
### Step 4: Install Tailwind CSS
To style your website, install Tailwind CSS, PostCSS, and Autoprefixer:
```bash
npm install -D tailwindcss postcss autoprefixer
```
### Step 5: Initialize Tailwind CSS
```bash
npx tailwindcss init -p
```
### Step 6: Start the Development Server
To start the development server, run
```bash
npm run dev
```
# Setting Up the Server Folder

Follow these steps to correctly set up the server folder for your project:

## Step 1: Close Existing Files

Before proceeding, close all currently open files related to the "app" folder.

## Step 2: Create a Server Folder

Create a folder named "server" in your project's root directory.

## Step 3: Navigate to the Server Folder

Open your terminal and navigate to the newly created "server" folder using the following commands:

```bash
cd ..
```
```bash
cd ./server/     # Navigate directly to the folder
```

### Step 4: Initialize a Node.js Package
```bash
npm init -y
```
### Step 5: Install Server Dependencies
Install the necessary dependencies for your server. These dependencies include cloudinary, cors, dotenv, express, mongoose, nodemon, and openai. Use the following command to install them
```bash
npm install cloudinary cors dotenv express mongoose nodemon openai
```
### Step 6: Start the Server
Start the server by running the following command within the "server" folder
```bash
npm start
```
# Creating an OpenAI API Key

To integrate OpenAI's capabilities into your project, follow these steps to obtain an API key:

1. Visit the [OpenAI API Key](https://platform.openai.com/account/api-keys) page on the OpenAI platform.

2. Create a new API key by clicking the "Create New Key" or similar button. You may need to sign in or create an account if you haven't already.

3. Once the API key is generated, copy it to your clipboard.

4. Create a file named `.env` in the "server" folder of your project.

5. Open the `.env` file and paste your OpenAI API key into it. The file should look like this `OPENAI_API_KEY=your-api-key-here` and Save the `.env`file.
   
# Acknowledgments

I would like to give credit to the [JavaScript Mastery](https://youtube.com/@javascriptmastery?si=xaR79Ck6_QOfWIAr) for providing valuable tutorials and insights that were instrumental in the development of this project.

