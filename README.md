# bafa.nvim

Minimal BufExplorer alternative.

## Requirements

- [Neovim](https://github.com/neovim/neovim) (tested with 0.9.0)
- [plenary.nvim](https://github.com/nvim-lua/plenary.nvim)

## Installation

Via [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
require('lazy').setup({
  -- Buffer management
  { 'mistweaverco/bafa.nvim', dependencies = 'nvim-lua/plenary.nvim' },
})
```

## Public methods

### `require('bafa.ui').toggle()`

Opens up a floating window with your buffers.

Press enter to select a buffer or press `dd` or `D` to delete a buffer.

![](bafa.gif)