# npm-test — React Package Testing Playground

A Create React App (CRA) sandbox for experimenting with and testing npm packages.

[![CI](https://github.com/xabierlameiro/npm-test/actions/workflows/ci.yml/badge.svg)](https://github.com/xabierlameiro/npm-test/actions/workflows/ci.yml)

## Purpose

This is a personal throwaway project for quickly evaluating npm packages, testing React patterns, and experimenting with new libraries without polluting other projects.

## Stack

| Layer           | Choice              |
| --------------- | ------------------- |
| Framework       | Create React App    |
| Language        | TypeScript          |
| Testing         | Jest                |
| Package manager | npm                 |

## Getting started

```bash
git clone https://github.com/xabierlameiro/npm-test.git
cd npm-test
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000).

## Scripts

| Script                       | Description                 |
| ---------------------------- | --------------------------- |
| `npm start`                  | Start development server    |
| `npm run build`              | Production build            |
| `npm test`                   | Jest tests (watch mode)     |
| `npm test -- --watchAll=false` | Jest tests (CI mode)      |

## License

[MIT](./LICENSE) — © 2026 Xabier Lameiro
