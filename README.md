# gps-bar 

A Neovim plugin that shows the file name and nvim-gps on Neovim 0.8's new 'winbar' feature. Helps you see each buffer's file name and where you are in the code. 

## Requirements

- Neovim 0.8 nightly
- nvim-gps
- nvim-treesitter
- nvim-web-devicons

## Installation

Use your favorite Neovim package manager:

```lua
-- Lua
use({
  "SmiteshP/nvim-gps",
  requires = "nvim-treesitter/nvim-treesitter",
  config = function ()
    require("nvim-gps").setup()
  end
})

use({
  "notken12/gps-bar", 
  requires = {"nvim-web-devicons", "nvim-gps"},
  config = function () 
    require("gps-bar").setup()
  end
})
```
