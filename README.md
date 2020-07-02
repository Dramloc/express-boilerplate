# express-mongoose-template

Simple template using express and mongoose for building REST APIs.

## Usage

- Install dependencies:
  ```shell
  yarn
  ```
- Copy `.env.example` and rename it to `.env` for a default configuration.
- Run project:
  ```shell
  yarn start
  ```

## Available scripts

### `yarn start`

Runs the project in the development mode.
API will be served on [http://localhost:8080](http://localhost:8080).

The project will reload using `nodemon` if you make edits.
You can see any `babel` compilation error in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.
This will run tests using `jest` and lint files using `eslint`.

### `yarn coverage`

Collect test coverage with `jest`.
Coverage report will be reported in the console and in the `coverage` folder.

### `yarn lint`

Lint project files using `eslint`.
You can run `yarn lint --fix` to autofix fixable issues.

### `yarn build`

Build project using `babel` to make it ready for production.
This should be run before launching `yarn serve`.

### `yarn serve`

Runs the project in production mode. Make sure you run `yarn build` before this script.

## Configuration

Application configuration is provided by environment variables and accessed in code with `process.env.VARIABLE_NAME`.

In order to share configurations, you can add a `.env` file at the root of the project.
You can copy `.env.example` and rename it to `.env` for a default configuration.

> If new environment variables are required by the app, they can be added to the `.env.example` to document them.
