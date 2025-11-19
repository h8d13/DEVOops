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

> Creates a symlink so you can call `code .` to open in current working directory

3rd: `./setup_asap` 

> Extension inspired by David P. Cahill `Select after paste` but in raw JS. 
> Also sets zsh default for VSCodium and hot reload `CTRL + F5`

4th: `./mods`

> Downloads 4 essential zsh plugins placed in `~/.config/zsh/$plugin_name`
> Provides prompts: zshrc, bashrc, shared aliases, env file

> Sets-up local bin and example script `hello`
> Firefox profiles: Ublock and about:blank default

>[!TIP]
> Any of them can be removed by simply deleting in the `k/` [dir](./k/) 

Other tweaks & Demo
---

- Auto indent after paste

[Demo.webm](https://github.com/user-attachments/assets/72da25db-1a02-4ba3-a091-fc8dfb809380)

Further tools
---

- https://open-vsx.org/vscode/item?itemName=timonwong.shellcheck
- https://open-vsx.org/vscode/item?itemName=ms-pyright.pyright

See [guided](./guided/) setups for GPG and SSH. 