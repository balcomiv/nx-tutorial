# NxTutorial

This project was generated using [Nx](https://nx.dev).

<p align="center"><img src="https://raw.githubusercontent.com/nrwl/nx/master/nx-logo.png" width="450"></p>

🔎 **Nx is a set of Extensible Dev Tools for Monorepos.**

## Quick Start & Documentation

[Nx Documentation](https://nx.dev/angular)

[10-minute video showing all Nx features](https://nx.dev/angular/getting-started/what-is-nx)

[Interactive Tutorial](https://nx.dev/angular/tutorial/01-create-application)

## Adding capabilities to your workspace

Nx supports many plugins which add capabilities for developing different types of applications and different tools.

These capabilities include generating applications, libraries, etc as well as the devtools to test, and build projects as well.

Below are some plugins which you can add to your workspace:

- [Angular](https://angular.io)
  - `ng add @nrwl/angular`
- [React](https://reactjs.org)
  - `ng add @nrwl/react`
- Web (no framework frontends)
  - `ng add @nrwl/web`
- [Nest](https://nestjs.com)
  - `ng add @nrwl/nest`
- [Express](https://expressjs.com)
  - `ng add @nrwl/express`
- [Node](https://nodejs.org)
  - `ng add @nrwl/node`

## Generate an application

Run `ng g @nrwl/angular:app my-app` to generate an application.

> You can use any of the plugins above to generate applications as well.

When using Nx, you can create multiple applications and libraries in the same workspace.

## Generate a library

Run `ng g @nrwl/angular:lib my-lib` to generate a library.

> You can also use any of the plugins above to generate libraries as well.

Libraries are sharable across libraries and applications. They can be imported from `@nx-tutorial/mylib`.

## Development server

Run `ng serve my-app` for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng g component my-component --project=my-app` to generate a new component.

## Build

Run `ng build my-app` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test my-app` to execute the unit tests via [Jest](https://jestjs.io).

Run `nx affected:test` to execute the unit tests affected by a change.

## Running end-to-end tests

Run `ng e2e my-app` to execute the end-to-end tests via [Cypress](https://www.cypress.io).

Run `nx affected:e2e` to execute the end-to-end tests affected by a change.

## Understand your workspace

Run `nx dep-graph` to see a diagram of the dependencies of your projects.

## Further help

Visit the [Nx Documentation](https://nx.dev/angular) to learn more.

## Commands Used

- ng g @nrwl/nest:app api --frontendProject=todos
- ng g @nrwl/workspace:lib data
- ng g @nrwl/angular:lib ui
- ng g component todos --project=ui --export
- ng add @nrwl/storybook
- ng g @nrwl/angular:storybook-configuration ui
- ng run ui:storybook
- ng run ui-e2e:e2e --watch

### Testing

- ng e2e todos-e2e --watch

## Kill Process Running on Port

- netstat -ano|findstr "PID :8081"
- taskkill /pid 18264 /f

## Helpful Links

### Storybook Integration

- https://blog.nrwl.io/ui-testing-with-storybook-and-nx-4b86975224c

### Misc

- https://github.com/sitepoint-editors/angular-todo-app/tree/part-1/src

### Toggle between editor and temrinal

- https://stackoverflow.com/questions/42796887/switch-focus-between-editor-and-integrated-terminal-in-visual-studio-code

## Reverse Proxy

- https://medium.com/bb-tutorials-and-thoughts/angular-how-to-proxy-to-backend-server-6fb37ef0d025
