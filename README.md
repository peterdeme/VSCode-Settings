# VSCode Settings

(Preface: I got the idea from [alefragnani](https://github.com/alefragnani/vscode-settings).)

My personal Visual Studio Code settings.

*I'm keeping it here because I want to have it synced between different machines.*

## Syncing (using Symlink)

### Windows

```
cd %HOMEPATH%/Documents/Git/vscode-settings/
mklink /H %HOMEPATH%\AppData\Roaming\Code\User\settings.json settings.json
mklink /H %HOMEPATH%\AppData\Roaming\Code\User\keybindings.json keybindings.json
mklink /H %HOMEPATH%\AppData\Roaming\Code\User\tasks.json tasks.json
```

### MacOS

```
cd ~/Documents/git/VSCode-Settings/
ln -h settings.json ~/Library/Application\ Support/Code/User/settings.json
ln -h keybindings.json ~/Library/Application\ Support/Code/User/keybindings.json
ln -h tasks.json ~/Library/Application\ Support/Code/User/tasks.json
```

## Installed Extensions

### Checking

```
$ code --list-extensions
```

### Installing

```
code --install-extension bungcip.better-toml
code --install-extension eamodio.gitlens
code --install-extension fwcd.kotlin
code --install-extension GitHub.vscode-pull-request-github
code --install-extension hbenl.vscode-mocha-test-adapter
code --install-extension hbenl.vscode-test-explorer
code --install-extension littlefoxteam.vscode-python-test-adapter
code --install-extension ms-azuretools.vscode-docker
code --install-extension ms-python.python
code --install-extension ms-vscode-remote.remote-containers
code --install-extension ms-vscode.vscode-typescript-tslint-plugin
code --install-extension msjsdiag.debugger-for-chrome
code --install-extension PKief.material-icon-theme
code --install-extension rduldulao.py-coverage-view
code --install-extension VisualStudioExptTeam.vscodeintellicode
code --install-extension xmonader.vscode-capnp
code --install-extension yzhang.markdown-all-in-one
code --install-extension zhuangtongfa.material-theme
