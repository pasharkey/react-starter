# react-starter

### VSCode Workspace Settings
The linting and prettier formatting can be applied automatically in VSCode when saving changes to a file by applies the following Workspace Settings:
```json
{
    "editor.formatOnSave": true,
    "eslint.autoFixOnSave": true,
    "eslint.alwaysShowStatus": true
}
```

### Development Server
Uses Webpack 4 development server with hot reload. To start the webpack development server run the following command: 
```sh
$ npm run dev
```

### Testing
Uses Jest & Enzyme to perform all tests. Tests are located in the /src/tests folder 

To excute all tests run:
```sh
$ npm run test
```

To update snapshots during testing run:
```sh
$ npm run test:update
```

To get test coverage report run:
```sh
$ npm run test:coverage
```

### Prettier
Uses prettier for code formatting with the following configurations located in the .prettierrc.json file in the project root
```json
{
    "printWidth": 120,
    "tabWidth": 2,
    "singleQuote": true,
    "trailingComma": "none",
    "bracketSpacing": true,
    "jsxBracketSameLine": false,
    "semi": true,
    "useTabs": false
}
```
Execute prettier against entire project via command line:
```sh
$ npm run format
```

### Linter
This project uses ESLint with the [Airbnb javascript styleguide](https://github.com/airbnb/javascript)

There is a built in webpack script that can perform linting against the project by running:
```sh
$ npm run lint
```

### Production
To package the project for a production deployment run the following command:
```sh
$ npm run build
```

## Contributors
* Patrick Sharkey (patrick.sharkey@gmail.com)

## License
MIT License. © 2018 Patrick Sharkey
