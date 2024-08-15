# Description
A package with Prettier configurations. The goal is to unify Prettier configurations for my projects.

## Usage
1. Install package via npm:

```
npm i -D @qimijoy/prettier-config
```

2. Add the required configuration in `prettier.config.js` (Prettier configuration file) in your project:

```
import primaryConfig from '@qimijoy/prettier-config/configs/primary.js';

export default {
	...primaryConfig,
};
```

## Adding new configurations
Put the configurations in the configs folder. Each configuration is an ES-module that exports an object.
https://prettier.io/docs/en/configuration.html#sharing-configurations
