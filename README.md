# VSCode Installation

VSCode is an **Integrated Development Environment (IDE)**, a tool used to build software. Often praised by its simplicity and extensibility, we will be using this platform for our exercises.

You can download it at the [official website](https://code.visualstudio.com/Download). Download the installer, run it and follow the installation steps.

![image](https://github.tools.sap/user-attachments/assets/14a15382-3981-476c-b4ab-05ca6669d03a)

# Recommended Extensions

Extensions add functionality to VSCode. You can install them from the Extensions panel (`Ctrl+Shift+X`). The following are recommended for this course:

- **[Prettier - Code Formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)** (`esbenp.prettier-vscode`) — automatically formats your JavaScript and TypeScript files so the code stays consistent and readable.
- **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)** (`dbaeumer.vscode-eslint`) — highlights code quality issues and common mistakes as you type.

> Please note, VSCode comes with builtin Javascript + Typescript support, so an LSP is not necessary for these languages

# Node.js Installation

Node.js is a JavaScript runtime that lets you run JavaScript code outside of the browser — directly on your machine. It is required for running the exercises, which are written in **JavaScript** and **TypeScript**.

- **JavaScript** runs directly on Node.js.
- **TypeScript** is a typed superset of JavaScript. Node.js does not execute TypeScript directly, but it provides the ecosystem to compile and run TypeScript files.

To install Node.js, follow the instructions at the [official download page](https://nodejs.org/en/download). Run the installer and follow the steps — this will also install `npm` (Node Package Manager), which you will use to manage dependencies throughout the exercises.

# Git Installation

Git is a version control system used to track changes in code. You will use it throughout the exercises to download challenge repositories and submit your work.

To install Git, go to the [official download page](https://git-scm.com/install), download the installer for your operating system, and follow the setup steps. Select the default options during installation if you are not sure.

After installing, verify it worked by opening a terminal and running:

```
git --version
```

You should see a version number printed, such as `git version 2.x.x`.
