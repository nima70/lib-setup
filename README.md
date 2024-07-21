# Simple TypeScript Library Setup

This repository provides a base setup for a TypeScript library, including configuration for publishing to AWS CodeArtifact. The setup ensures you can switch between using local dependencies and CodeArtifact based on the environment.

## Project Structure

```
my-typescript-package/
├── src/
│ └── index.ts
├── .gitignore
├── .npmrc
├── package.json
├── tsconfig.json
├── setup-npmrc.js
├── .env
├── .env.local
├── .env.prod
└── README.md
```

### Prerequisites

- Node.js and npm installed