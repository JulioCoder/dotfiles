# Setting up the New Macbook M1 apple ARM for web development - 2021

1. Search the Terminal.app in Applications
1. Right click on Terminal > Get Info > Check Open with Rosseta
1. Once on Terminal.app run this command
> xcode-select --install
1. Go to this website: https://brew.sh then copy the link


# dotfiles

Those are my main settings

#### vscode-extensions.txt

With Terminal, inside dev folder, create file vscode-extensions.txt and paste it, then run this command:

> while read line; do code --install-extension "$line";done < vscode-extensions.txt

#### vscode-settings

In vscode press Cmd + Shift + P then searcch for Open Settings (JSON) and paste it. 

#### vscode-keybindings.json

Search inside vscode Ctrl + Shift + p --> Open Keyboard Shortcuts (JSON) and paste it


