# DEVOoOps

Goal is to make a dev **faster** than the next. Assumes fresh installation.

Also useful and pretty:
```
┌──[12:03]─[hadean_$@vasex]─[~/somewhere]─[12:02]─[git:master*]-[.venv]
└──╼ $
```

Setup & Usage
---

>[!TIP]
> None of these scripts require sudo. Will prompt when required. Also all defs are found in [header file.](./k/00_header) 

1st: `./deps`

> To check you have all needed.

2nd: `./setup_vs`

> Downloads latest release of VSCodium installs to `/opt/vscodium`

> Creates a symlink so you can call `code .` to open in current working directory. **Open it once** to generate the vs-oss files.

3rd: `./setup_asap`

> Extension inspired by David P. Cahill `Select after paste` but in raw JS.
> Also sets zsh default for VSCodium and hot reload `CTRL + F5` and auto-indent after paste + word-wrap

Open VSCodium again to check it works.

4th: `./mods`

> Downloads 4 essential zsh plugins placed in `~/.config/zsh/$plugin_name`
> Provides prompts: zshrc, bashrc, shared aliases, env file

> Sets-up local bin and example script `hello`

Aliases can be edited in `~/.config/aliases` or using `ecomms` then `srcall` after adding something new (or open a new shell.)

Env is controlled through `.config/environment`

`Fzf/fd` shortcuts are:

- Ctrl+T: "Find and paste a path" (files + dirs)
- Alt+C: "Go to a directory" (dirs only, executes cd)
- Ctrl+R: "Search command history" (you already know this)

You can also pipe to these directly or use them in scripts.

>[!NOTE]
> Any of them can be removed by simply deleting in the `k/` [dir](./k/) in [examples](./examples/)
Firefox profiles: Ublock and about:blank default

Remove checks from `00_header_checks`, adapt examples to liking/according to what you removed.

Further tools
---

- https://open-vsx.org/vscode/item?itemName=timonwong.shellcheck
- https://open-vsx.org/vscode/item?itemName=ms-pyright.pyright
- https://open-vsx.org/vscode/item?itemName=charliermarsh.ruff
- https://open-vsx.org/vscode/item?itemName=shardulm94.trailing-spaces

See [guided](./guided/) setups for GPG and SSH.