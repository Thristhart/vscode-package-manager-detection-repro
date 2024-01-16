This is a simple environment to aid in reproduction of [this vscode issue](https://github.com/microsoft/vscode/issues/202551). To reproduce:
- Open vscode-package-manager-detection-repro.code-workspace in vscode
- Open the "NPM Scripts" sidebar view
- Right click on a package.json and click "Run Install"
- vscode will incorrectly identify the project as a Yarn project and run Yarn install.