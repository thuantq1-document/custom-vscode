# Custom Vscode

## Install plugin
- eslint: check syntax code with .eslintrc.js
- editorconfig: can read .editorconfig file
- docker
- remote-wsl
- gitlens
- vscode-icons

## Setting

```bash
{
    // Start ruler
    "editor.rulers": [
        80
    ],
    "workbench.colorCustomizations": {
        "editorRuler.foreground": "#ff4081"
    },
    // End ruler
    // Start show space
    "editor.renderWhitespace": "all",
    // End show space
    // Start theme
    "workbench.iconTheme": "vscode-icons",
    "workbench.colorTheme": "Monokai Dimmed",
    // End theme
    // Start auto save
    "files.autoSave": "afterDelay",
    // End auto save
    // Start setup terminal
    "terminal.integrated.shell.windows": "D:\\Software\\Git\\Setup\\bin\\bash.exe",
    // End setup terminal
    // Start docker
    "docker.containers.groupBy": "Registry",
    "docker.images.groupBy": "RepositoryName",
    "docker.volumes.groupBy": "VolumeName",
    // End docker
}
```