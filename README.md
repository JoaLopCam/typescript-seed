# Typescript + Jest testing coverage + tslint UPDATED(10/02/2019)

- [TypeScript](https://www.typescriptlang.org) 3.3.3 setup for experimental decorator support

- [Jest](http://facebook.github.io/jest/) as a testing platform

- [TSLint](https://github.com/palantir/tslint) TSLint is an extensible static analysis tool that checks TypeScript code for readability, maintainability, and functionality errors

## General Packages

| ✔ | [Node.js](http://nodejs.org/) | >= 8.0 | [nvm](https://github.com/creationix/nvm) is highly recommended for managing multiple node versions on a single machine |

| ✔ | [Visual Studio Code](https://code.visualstudio.com/) | >= 1.14 | We'll be using several specific features of the VS Code editor. |

## VS Code Extensions

| ✔ | [tslint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint) | Static code analysis for JavaScript and TypeScript files |

| ✔ | [jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest) | Syntax highlighting for [Jest snapshot testing](https://facebook.github.io/jest/docs/snapshot-testing.html) and in-editor test pass/fail statuses |

| ✔ | [Prettier formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) | VS Code package to format your JavaScript / TypeScript

## Global Node.js Packages

```

npm install -g <package-name>

```

| ✔ | [ts-node](https://github.com/TypeStrong/ts-node) |^8.0.2 |

| ✔ | [typescript](https://github.com/microsoft/typescript) | ^3.3.3 |

| ✔ | [tslint](https://github.com/palantir/tslint) | ^5.12.1 |

| ✔ | [parcel-budnler](https://github.com/parcel-bundler/parcel) | ^1.11.0 |

## Dependencies

```

npm install -D <package-name>

```

| ✔ | [tslint-config-airbnb](https://www.npmjs.com/package/tslint-config-airbnb) |^5.11.1 |

| ✔ | [typescript](https://github.com/microsoft/typescript) | ^3.3.3 |

| ✔ | [tslint](https://github.com/palantir/tslint) | ^5.12.1 |

| ✔ | [parcel-budnler](https://github.com/parcel-bundler/parcel) | ^1.11.0 |

| ✔ | [@types/jest](https://www.npmjs.com/package/@types/jest) | ^24.0.0 |

| ✔ | [@types/node](https://www.npmjs.com/package/@types/node) | ^10.12.24 |

## Project setup

```

git clone https://github.com/JoaLopCam/typescript-seed

cd typescript-seed

npm install

```

### How to use it

##### Compile all .ts files to .js in /dist folder

`npm run compile`

##### Run one test or all test

`npm run test {filename}`
`npm run test`

##### identifying and reporting rules

`npm run lint`
