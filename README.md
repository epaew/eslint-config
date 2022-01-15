# @epaew/eslint-config

## How to use
### Install
```sh
yarn add -D eslint @epaew/eslint-config
```

### Configuration
* .eslintrc.yaml
    ```yaml
    root: true
    extends:
      # Select one of the following
      - @epaew
      - @epaew/eslint-config/jest
      - @epaew/eslint-config/node
      - @epaew/eslint-config/react
      - @epaew/eslint-config/react-native

      - @epaew/eslint-config/typescript
      - @epaew/eslint-config/jest-typescript
      - @epaew/eslint-config/node-typescript
      - @epaew/eslint-config/react-typescript
      - @epaew/eslint-config/react-native-typescript
    ```

## LICENSE
[MIT](./LICENSE)
