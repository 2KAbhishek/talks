# The Laziest Neovim

**Why do you use Neovim?**

> Efficiency? Customizability? Fun?

---

```lua
local about_me = {
    name = "Abhishek Keshri"
    alias = "2KAbhishek"
    job = "Tech Lead @ Incubyte"
    shell = "zsh | powershell"
    os = "linux | macos | windows | android"
    terminal = "foot | iterm | windows terminal | termux"
    language = "ruby, typescript, python, bash, lua and more..."
}
```

---

## What is lazy loading anyway?

> !eager loading

Lazy loading loads a plugin only if certain **condtions** are met.

- Events
- Commands
- Key Press
- Filetype

---

## Why should I care?

Gives you plugin less Nevoim like startup times!

### Stats

For 79 plugins it gives me ~**10X** Faster startup times

- Linux Workstation: ~**300ms** -> **~28 ms**
- M2 Mini: ~**360 ms** -> **~32 ms**
- Windows System: ~**400 ms** -> ~**42 ms**
- Android Phone: ~**660 ms** -> ~**56 ms**
- Android Tablet: ~**1150 ms** -> ~**106 ms**

> If a plugin breaks during an upgrade, it won't affect your workflow

---

## Events

> :help events

- **BufReadPre**, **BufNewFile**: Triggered before reading a file into buffer.

  - Plugins that affect the buffer behaviour
  - `treesitter`, `lsp-zero`, `lualine`, `gitsigns`

- **InsertEnter**: Triggered when entering insert mode

  - Plugins that are used in insert mode
  - `cmp`, `copilot`, `LuaSnip`, `autopairs`

- **LspAttach**: Triggered after Lsp is active

  - Plugins that depend on of functioning LSP
  - `lsp-saga`, `lsp-lines`

- **VeryLazy**: Loaded at the end of lazy lifecycle (*:Lazy profile*)
  - Plugins that should be loaded, but are not priority, also useful for conditional loads
  - `which-key`, `notify`, `tmux`

---

## Commands

> Plugins that you want to load when a specific command is triggered

- `nvim-tree`: *cmd = 'NvimTreeToggle'*
- `telescope`: *cmd = 'Telescope'*
- `co-author`: *cmd = GitCoAuthors*
- `nerdy`: *cmd = Nerdy*
- `ccc`: *cmd = { 'CccHighlighterToggle', 'CccConvert', 'CccPick' }*

---

## Key Press

> Plugins that you want to load on specific key press

- `wilder`: *keys = { ':', '/', '?', }*
- `surround`: *keys = { 'cs', 'ds', 'ys' }*
- `comment`
- `flash`

---

## Filetype

> Plugins that you want to load for specific file types

- `neodev`: *ft = { 'lua', 'vim' }*
- `rails`: *ft = 'ruby'*
- `markdown-preview`: *ft = 'markdown', cmd = 'MarkdownPreviewToggle'*

> Lazy loading conditions can be combined

---

## Links

[nvim2k](https://github.com/2KAbhishek/nvim2k)

[lazy spec](https://github.com/2KAbhishek/nvim2k/blob/main/lua/plugins/list.lua)

[Link to slides](https://github.com/2KAbhishek/talks/blob/main/the-laziest-neovim.md)

---
# That's All Folks!

[2KAbhishek@GitHub](https://github.com/2KAbhishek)

[2KAbhishek@Twitter](https://twitter.com/2KAbhishek)

[2KAbhishek@YouTube](https://youtube.com/2KAbhishek)

