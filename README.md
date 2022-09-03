# OpenSCD

This repository hosts SCL related functionality on top of [OpenSCD core](https://github.com/openscd/open-scd-core)

## Linting and formatting

To scan the project for linting and formatting errors, run

```sh
npm run lint
```

To automatically fix linting and formatting errors, run

```sh
npm run format
```

We use ESLint and Prettier for linting and formatting. Plugins for automatic
formatting and linting during editing are available for vim, emacs, VSCode,
and all popular IDEs.

## Testing with Web Test Runner

To execute a single test run:

```sh
npm test
```

To run the tests in interactive watch mode run:

```sh
npm run test:watch
```

## Tooling configs

For most of the tools, the configuration is in the `package.json` to reduce the
amount of files in the project.

## Local Demo with `web-dev-server`

```sh
npm start
```

To run a local development server that serves the basic demo located in `demo/index.html`

> Webcomponents in this repository follow the [open-wc](https://github.com/open-wc/open-wc) recommendation.

## License

This project is licensed under the [Apache License 2.0](LICENSE).

&copy; Jakob Vogelsang, Christian Dinkel
