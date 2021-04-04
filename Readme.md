# coc-pairs

Forked from [neoclide/coc-pairs](https://github.com/neoclide/coc-pairs). The plugin is currently not smart enough if you want to add brackets within the code. Because of Issue [#28](https://github.com/neoclide/coc-pairs/issues/28) I have created a fork which activates the auto pairs function only at the end of the line.

## Install

Install build dependencies on Arch Linux:

```bash
sudo pacman -Sy yarn
```

Install this plugin with [Plug](https://github.com/junegunn/vim-plug): Add to your `init.vim`:

```
Plug 'niki-on-github/coc-pairs', {'do': 'yarn install --frozen-lockfile && yarn build'}
```

Make sure you have uninstalled the original plugin via `:CocUninstall coc-pairs`. Then install the patched plugin with `PlugInstall`.

## Features

- Insert pair characters automatically only at the end of an line.

## License

MIT
