# Neovim Cheatsheet

## Word Navigation
- `w` - move to beginning of next word
- `b` - move to beginning of previous word
- `e` - move to end of current word
- `W`, `B`, `E` - same as above but for WORD (whitespace-separated)

## Go to Definition & Navigation
- `grd` - go to definition
- `<C-t>` - jump back to previous location
- `gri` - go to implementation
- `grt` - go to type definition
- `grr` - find references
- `grn` - rename symbol
- `gra` - code actions

## Preview/Hover
- `K` - show hover information (like VSCode hover)
- `<C-k>` - toggle signature help while in insert mode
- `<leader>q` - open diagnostic quickfix list
- `]d` / `[d` - next/previous diagnostic

## File Operations
- `:edit filename` or `:e filename` - open/create new file
- `:new filename` - create in horizontal split
- `:vnew filename` - create in vertical split

## Search & Find
- `<leader>sf` - search files (Telescope)
- `<leader>sg` - live grep (search in files)
- `<leader>sh` - search help
- `<leader>sn` - search Neovim config files
- `<leader>sw` - search current word
- `<leader>sr` - search resume (last search)

## Theme Selection
- `:colorscheme tokyonight-night` - dark theme (current)
- `:colorscheme tokyonight-storm` - dark with blue tint
- `:colorscheme tokyonight-moon` - dark with purple tint
- `:colorscheme tokyonight-day` - light theme
- `:Telescope colorscheme` - browse all themes

## Window Management
- `<C-h>` - move to left window
- `<C-l>` - move to right window
- `<C-j>` - move to lower window
- `<C-k>` - move to upper window

## Basic Vim Commands
- `i` - insert mode
- `<Esc>` - normal mode
- `:w` - save file
- `:q` - quit
- `:wq` - save and quit
- `u` - undo
- `<C-r>` - redo