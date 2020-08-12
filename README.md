# Typescript Seed project

A basic seed project for building application with NodeJS, Typescript, Jest and ESLint.

## Features:

- Typescript installed as a dev dependency and configured with sensible defaults.
- Eslint with Typescript and Prettier plugins with recommended defaults.
- Your code goes inside the `src` folder.
- Jest for testing.

### Developing

`npm run dev`
Uses nodemon and ts-node for fast development cycle.

`npm dev:inspect`
Same as above but with `--inspect-brk` flag so you can debug using Chrome DevTools.
For more information please read this https://medium.com/@paul_irish/debugging-node-js-nightlies-with-chrome-devtools-7c4a1b95ae27.

## Developing

1. `npm install` dependencies.

2. `npm run dev` or `npm run dev:inspect` to start developing.

3. Run tests with `npm test` or `npm run test:watch` for watch mode.

4. `npm run lint` for linting.

## Building and running your application

1. `npm build` will transpile the application and save in the `./build` folder (sourcemaps included).

2. `npm start` to run the build.

## License

MIT.
