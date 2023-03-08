# parcel-boilerplate

Boilerplate project with:
- [Parcel](https://github.com/parcel-bundler/parcel)
- [Eslint](https://github.com/eslint/eslint)
- [Typescript](https://github.com/microsoft/TypeScript)
- [Sass](https://github.com/sass/sass)

## Getting started

To run the project locally, run:
```shell
npm run dev
```
This will build the project and watch for changes.
Open your browser at [http://localhost:1234/](http://localhost:1234/) to view your project.
Happy coding! 🎉

## Linting
Eslint is installed and preconfigured to check your JS/TS code.
Run
```shell
npm run lint
```
to run the linter and show which problems it detects. Add the `--fix` option to have it automatically fix the issues, like so:
```shell
npm run lint -- --fix
```

## Building
Run
```shell
npm run build
```
to create a production build with minified js, css and html.
The production build will be in the `dist` directory.