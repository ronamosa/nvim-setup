# Neovim+ Setup 

This repo is my customized version of the awesome [neovim from scratch](https://github.com/LunarVim/Neovim-from-scratch) project. Please go check that out for the original repo + setup.

## Setup 

Make sure to remove or move your current `nvim` directory

**IMPORTANT** requires `Neovim 0.6 release` version
```
git clone https://github.com/ronamosa/nvim-setup.git ~/.config/nvim
```

Run `nvim` and wait for the plugins to be installed 

**NOTE** (You will notice treesitter pulling in a bunch of parsers the next time you open Neovim) 

## Get healthy

Open `nvim` and enter the following:

```
:checkhealth
```

## Plugins 

- look at [pluings.lua](lua/user/plugins.lua) for list of plugins installed by default.

## Keybindings

important keys to know in order to utilize all functions.

read:

- [keymaps.lua](./lua/user/keymaps.lua)
- [whichkey.lua](./lua/user/whichkey.lua) 

```
# "leader" key is 'space'

# search
ctrl+f - find file
ctrl+F - grep

# files 
open = use search, enter on file opens new buffer.
close = :dw on cli, or <leader>+c to "close" buffer.

# key lookup
press leader key i.e. 'space' to open keymap menu.

# browser sidebar
press leader + e 

# navigate windows
shift + h = scroll buffers left
shift + l = scroll buffers right
```

