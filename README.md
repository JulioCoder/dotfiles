# Setting up the New Macbook M1 apple ARM for web development - 2021

#### Check Rosseta Option (Brew does not support apple ARM yet)

* Search the Terminal.app in Applications

* Right click on Terminal > Get Info > Check Open with Rosseta

#### Install Development tools

* Open the Terminal.app run this command

* ``xcode-select --install``

* If you want to remove this tools, then run ``sudo rm -rf /Library/Developer/CommandLineTools``

#### Install Brew

* Go to this website: https://brew.sh then copy the link

* Paste in Terminal

* 

# dotfiles

Those are my main settings

#### vscode-extensions.txt

With Terminal, inside dev folder, create file vscode-extensions.txt and paste it, then run this command:

> while read line; do code --install-extension "$line";done < vscode-extensions.txt

#### vscode-settings

In vscode press Cmd + Shift + P then searcch for Open Settings (JSON) and paste it. 

#### vscode-keybindings.json

Search inside vscode Ctrl + Shift + p --> Open Keyboard Shortcuts (JSON) and paste it


