# retroWire-nvim

Simple yet functional neovim statusLine plugin.

## Adding it to your config

Using [Lazy](https://github.com/folke/lazy.nvim)

Return this Lua table

```lua
{
    "tiwari-krishna/retroWire-nvim",
    config = function()
        require("retroWire")
    end,
}
```

Using [Packer](https://github.com/wbthomason/packer.nvim)

```lua
use {
    'tiwari-krishna/retroWire-nvim',
}
```
