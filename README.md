# LoginFrameworksInvestigation2025

This is educational repository to go through the current state (as for Jan 2025) of the major frameworks based on the implementation of the login page with same functional requirements.

## Content overview

todo: here will be the explanation of each project

## Getting started

todo: mocks-server

### Run tasks

To run the dev server for your app, use:

```sh
npx nx serve login-ang
```

To create a production bundle:

```sh
npx nx build login-ang
```

To see all available targets to run for a project, run:

```sh
npx nx show project login-ang
```

These targets are either [inferred automatically](https://nx.dev/concepts/inferred-tasks?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) or defined in the `project.json` or `package.json` files.

### Add new projects

While you could add new projects to your workspace manually, you might want to leverage [Nx plugins](https://nx.dev/concepts/nx-plugins?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) and their [code generation](https://nx.dev/features/generate-code?utm_source=nx_project&utm_medium=readme&utm_campaign=nx_projects) feature.

Use the plugin's generator to create new projects.

To generate a new application, use:

```sh
npx nx g @nx/angular:app demo
```

To generate a new library, use:

```sh
npx nx g @nx/angular:lib mylib
```
