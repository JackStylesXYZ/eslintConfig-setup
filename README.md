# eslintConfig-setup

`yarn add eslint --dev`

`yarn add eslint-plugin-jsx-a11y --dev`

Under package.json file find the `eslintConfig` option - it can be configured in multiple ways:

### Warn

```
  "eslintConfig": {
    "extends": [
      "react-app"
    ],
    "plugins": [
      "jsx-a11y"
    ],
    "rules": {
        "jsx-a11y/alt-text":"warn"
    }
  }
```

### Recommend

```
  "eslintConfig": {
    "extends": [
      "react-app",
      "plugin:jsx-a11y/recommend"
    ],
    "plugins": [
      "jsx-a11y"
    ]
  }
```

### Strict

```
  "eslintConfig": {
    "extends": [
      "react-app",
      "plugin:jsx-a11y/strict"
    ],
    "plugins": [
      "jsx-a11y"
    ]
  }
```
