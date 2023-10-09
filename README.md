# flexoki-nvim
A nvim adaptation of flexoki by Steph Ango (stephango.com/flexoki)

This is an early version and is very simple, not feature rich.

## Installation
To install simply add via your plugin manager and call the theme

**[Paq](https://github.com/savq/paq-nvim)**

```lua
require('paq')({
  { 'stevedylandev/flexoki-nvim', as = 'flexoki' }
})
```

**[lazy.nvim](https://github.com/folke/lazy.nvim)**

```lua
require("lazy").setup({
  { 'stevedylandev/flexoki-nvim', name = 'flexoki' }
})
```

**[packer.nvim](https://github.com/wbthomason/packer.nvim)**

```lua
require('packer').startup(function(use)
  use({ 'stevedylandev/flexoki-nvim', as = 'flexoki' })
end)
```

```
-- Set colorscheme after options
vim.cmd('colorscheme flexoki')
```
