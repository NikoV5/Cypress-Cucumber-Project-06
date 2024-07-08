# Prerequisites

After cloning repository, you need to install these dependencies:
- Node Package Manager (NPM)
- Cypress
- Cucumber -> @badeball/cypress-cucumber-preprocessor
- Cucumber -> @bahmutov/cypress-esbuild-preprocessor -D

If you dont have the extensions already installed in VScode, you will need these for cucumber to work:
- Cucumber (Gherkin) Full Support -> Alexander Krechik
- Cuke Step Definition Generator -> Muralidharan Rajendran

## Initialize The Project

Once you open your framework, initialize it as a node.js project with the following command:

```bash
npm init -y
```

## Install Cypress

```bash
npm install cypress -D
```

## Install @badeball/cypress-cucumber-preprocessor
This preprocessor aims to provide a developer experience and behavior similar to that of Cucumber, to Cypress.

```bash
npm install @badeball/cypress-cucumber-preprocessor -D
```

## Install @bahmutov/cypress-esbuild-preprocessor

```bash
npm install @bahmutov/cypress-esbuild-preprocessor -D
```
