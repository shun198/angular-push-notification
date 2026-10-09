# Friendlychat

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.4.

Dependencies are installed with [pnpm](https://pnpm.io/) 10.33.4 (see the `packageManager` field). Cloud Functions live in `functions/` and use their own lockfile.

```bash
corepack enable
pnpm install
pnpm --dir functions install
```

## Development server

Run `pnpm start` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `pnpm exec ng generate component component-name` to generate a new component. You can also use `pnpm exec ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `pnpm build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `pnpm test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `pnpm exec ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
