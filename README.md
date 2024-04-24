# Node.js + TypeScript Boilerplate

Opinionated Node.js and TypeScript boilerplate

## 🚀 Included

- [Node.js](https://nodejs.org/) and [TypeScript](https://www.typescriptlang.org/), obviously
- [ESLint](https://eslint.org/) + [typescript-eslint](https://typescript-eslint.io/) for linting
- [Prettier](https://prettier.io/) for code formatting
- [Renovate](https://renovatebot.com/) for automatic dependency updates
- [Visual Studio Code](https://code.visualstudio.com/) workspace config

## 🌱 Inspired By

- [Nest.js](https://nestjs.com/) default project structure
- [Starting a TypeScript Project in 2021](https://www.metachris.com/2021/04/starting-a-typescript-project-in-2021/) by Chris Hager

## 📦 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/iipanda/node-typescript-boilerplate.git
```

2. Install [pnpm](https://pnpm.io/installation) if you haven't already. This project assumes pnpm and won't allow you to install dependencies with other package managers.

3. Install dependencies:

```bash
cd node-typescript-boilerplate
pnpm install
```

## 🛠 Scripts

- `build`: Compiles TypeScript to JavaScript
- `start`: Runs the compiled JavaScript
- `format`: Formats the code with Prettier
- `lint`: Lints the TypeScript code
- `lint:fix`: Lints and attempts to fix issues automatically

## 🚧 TODO

- Add Docker support
- Add import aliases

## 📄 License

This project is licensed under the [MIT License](LICENSE).
