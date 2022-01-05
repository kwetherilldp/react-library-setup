# react-library-setup
This project makes it easy to get your component library started.

* [Maintainers](#maintainers)
* [Usage](#usage)
* [Development](#development)


## <a name="maintainers"></a>Maintainers
* Kirk Wetherill <kwetherill@digitalpharmacist.com>
* Digitial Pharmacist - Product

## <a name="usage"></a>Usage
Application developers that want to consume this component should install the package using npm:

```bash
npm i
npm storybook
```

## <a name="development"></a>Development

| Script | Description |
|---|---|
| `npm install` | Install the project dependencies; once installed `npm run build` is also executed |
| `npm storybook` | The the Storybook server and open ina browser |
| `npm run build-storyook` | Compile Storybook documentation and output to /docs |
| `npm run build-lib` | Compile CSS and Javascript assets |
| `npm login` | Login to your NPM account by entering your username and password |
| `npm publish` | Push changes to NPM account based on the package.json name property |
| `npm run test` | Run unit tests, stylelint, eslint and provide code coverage metrics |
| `npm run test:debug` | Run Jest in a Node process so you can debug within your test suite. This will pass the `--inspect-brk` flag and the `--runInBand` cli option to Jest. Add a `debugger; //eslint-disable-line` statement to the line in the test file you would like to break on. |
| `npm run test:unit` | Run unit tests only. |
| `npm run test:style` | Run linters to verify code meets the configured `eslint` settings |
| `npm run test:coverage` | Run `npm run test:unit` and provide metrics about coverage || `npm run upgrade-interactive` | Run `npm-check` to identify available dependency updates |
