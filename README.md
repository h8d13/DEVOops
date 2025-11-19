# DEVOops

Goal is to make a dev **faster** than the next. Assumes fresh installation.

Setup & Usage
---

>[!TIP]
> None of these scripts require sudo.

1st: `./deps` 

> To check you have all needed.

2nd: `./setup_vs` 

> Downloads latest release of VSCodium installs to `/opt/vscodium`

> Open vscodium once to generate the `/home/user/.vscode-oss` folder.

3rd: `./setup_asap` 

> Extension inspired by David P. Cahill `Select after paste` but in raw JS.
> You can then modify behavior: `/.vscode-oss/extensions/asap/extension.js`

4th: `./mods`

> Downloads 4 essential zsh plugins places in `~/.config/zsh/$plugin_name`
> Provides working zshrc to work with

Other tweaks & Demo
---

- Auto indent after paste
- Zsh integration to VSCodium terminal

[Demo.webm](https://github.com/user-attachments/assets/72da25db-1a02-4ba3-a091-fc8dfb809380)

Further tools
---

- https://open-vsx.org/vscode/item?itemName=timonwong.shellcheck
- https://open-vsx.org/vscode/item?itemName=ms-pyright.pyright

