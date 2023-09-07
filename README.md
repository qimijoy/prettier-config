# Description
A package with Prettier configurations. The goal is to unify Prettier configurations for my projects.

## Usage
1. Install package via npm:

```
npm i --save-dev @qimijoy/prettier-config
```

2. Add the required configuration in Prettier configuration file in your project:

```
const primaryConfig = require('@qimijoy/prettier-config/configs/primary');

module.exports = {
  ...primaryConfig,
};
```

## Adding new configurations
Put the configurations in the configs folder. Each configuration is a CommonJS module that exports an object.
https://prettier.io/docs/en/configuration.html#sharing-configurations
