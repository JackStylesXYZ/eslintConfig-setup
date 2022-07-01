# eslintConfig-setup

`yarn add eslint --dev`

`yarn add eslint-plugin-jsx-a11y --dev`

Under package.json file find the `eslintConfig` option - it can be configured in multiple ways:

```
  "eslintConfig": {
    "extends": [
      "react-app",
      "react-app/jest",
      "plugin:jsx-a11y/recommended"
    ],
    "plugins": [
      "jsx-a11y"
    ],
    "rules": {
        "jsx-a11y/alt-text":"warn"
    }
  }
```
