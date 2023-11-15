# Netblink Prettier Config

### Install Prettier
```bash
npm install -D prettier prettier-plugin-tailwindcss @shufo/prettier-plugin-blade @prettier/plugin-php
```

### Install Prettier Config
See: https://prettier.io/docs/en/configuration.html#sharing-configurations
```bash
npm install --dev @netblink/nb-prettier
```

### Config

##### VsCode
Open User Settings (json) press `ctrl+p` and type `>User Settings (JSON)`, then copy this:
```json
{
    "editor.formatOnSave": true,
    "editor.detectIndentation": false,
    "files.insertFinalNewline": true,
    "prettier.tabWidth": 4,
    "editor.inlineSuggest.enabled": true,
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[vue]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[scss]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[css]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[php]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[blade]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
}
```

#### Package.json
Add this config to your project package.json
```json
"prettier": "@netblink/nb-prettier",
```
