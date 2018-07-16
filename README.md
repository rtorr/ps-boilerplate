# PS-Boilerplate

This project aims to be a starting point for PureScript projects

## Develop

```bash
yarn start
```

## Test

```bash
yarn test
```

## Build

```bash
yarn build
```

## Notes:

### Getting started with PureScript

- [Install PureScript tools](https://github.com/purescript/documentation/blob/master/guides/Getting-Started.md)
- [Install psc-package](https://github.com/purescript/psc-package/releases)

### VSCode

- [Install vscode-ide-purescript](https://github.com/nwolverson/vscode-ide-purescript#installation-and-general-use)

### Package Documentation

- [Pursuit](https://pursuit.purescript.org/)

### Installing a new package

```bash
# install or update the dependencies listed in psc-package.json
psc-package install

# install or update the package and add it to psc-package.json if not listed
psc-package install <package>

# list available commands
psc-package --help
```

### Initializing a blank project

```bash
mkdir <project-name>
cd <project-name>
pulp --psc-package init
```
