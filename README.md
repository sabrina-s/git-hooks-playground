### Run linters

`npm run lint`

### Run linters + fix

`npm run lint -- --fix`

### Husky

Set up git hooks with Husky:

`npm run prepare`

Create a new hook:

e.g. `npx husky add .husky/pre-commit "npm test"`
