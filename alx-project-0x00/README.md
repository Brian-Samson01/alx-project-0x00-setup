# 0. Scaffolding a Next.js Project

## Project Description
This project covers the fundamentals of setting up a modern web application using Next.js, TypeScript, Tailwind CSS, and ESLint. The goal is to understand how to scaffold a project using CLI tools such as `npx` with `create-next-app`, and how different setup choices affect the project structure.

## Learning Objectives
- Scaffold a Next.js project using `create-next-app`
- Use CLI options and prompts to configure a project
- Enable TypeScript, ESLint, and Tailwind CSS
- Understand the difference between App Router and Pages Router
- Start and run a Next.js development server on a custom port

## Requirements
- Node.js v16 or later  
- npm  
- Visual Studio Code  
- Internet connection  

## Setup Instructions

### 1. Open Visual Studio Code
Start a new VS Code instance.

### 2. Open the Terminal
From the top menu:

### 3. Navigate to Your Project Directory
Use the terminal to move into the directory where you want your project created:
```bash
cd path/to/your/project-directory
npx create-next-app@latest alx-project-0x00 --typescript
npm run dev -- -p 3000
