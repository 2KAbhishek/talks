# The Laziest Neovim 

```lua
local about_me = {
    name = "Abhishek Keshri",
    alias = "2KAbhishek",
    job = "Tech Lead @ Incubyte",
    shell = "zsh | powershell",
    os = "linux | macos | windows | android",
    terminal = "foot | iterm | windows terminal | termux",
    language = "ruby, typescript, python, bash, lua and more...",
}
```

---

## Why do you use Neovim?

- Efficiency? 󰈏
- Blazingly fast ? 󱓞
- Personalisation? 
- Fun? 
- I use neovim btw? 󰱫
- All of the above! 

---

## What is lazy loading anyway?

> !eager loading

Lazy loading is a strategy to load a plugin only on certain **conditions**.

- Events 
- Commands 
- Keys 
- File Types 

---

## Why should I care?

Makes your neovim experience **blazingly fast** _without_ losing out on functionality.

### Stats 

For 79 plugins it gives me ~**10X** faster startup times

- Linux Workstation: ~**300ms** -> **~28 ms** 
- M2 Mini: ~**360 ms** -> **~32 ms** 
- Windows System: ~**400 ms** -> ~**42 ms** 
- Android Phone: ~**660 ms** -> ~**56 ms** 
- Android Tablet: ~**1150 ms** -> ~**106 ms** 

---

## Events 

> Load plugins on specific events _:help events_

- **BufReadPre**, **BufNewFile**: Triggered before reading a file into buffer.

  - Plugins that affect the buffer behaviour
  - `treesitter`, `lsp-zero`, `lualine`, `gitsigns`

- **InsertEnter**: Triggered when entering insert mode

  - Plugins that are used in insert mode
  - `cmp`, `copilot`, `LuaSnip`, `autopairs`

- **LspAttach**: Triggered after LSP is active

  - Plugins that depend on of functioning LSP
  - `lsp-saga`, `lsp-lines`

- **VeryLazy**: Loaded at the end of lazy life cycle (_:Lazy profile_)
  - Plugins that should be loaded, but are not priority
  - `which-key`, `notify`, `tmux`

---

## Commands 

> Load plugins on specific commands

- `nvim-tree`: _cmd = 'NvimTreeToggle'_
- `telescope`: _cmd = 'Telescope'_
- `co-author`: _cmd = GitCoAuthors_
- `nerdy`: _cmd = Nerdy_
- `ccc`: _cmd = { 'CccHighlighterToggle', 'CccConvert', 'CccPick' }_

---

## Keys 

> Load plugins on specific keys

- `wilder`: _keys = { ':', '/', '?', }_
- `surround`: _keys = { 'cs', 'ds', 'ys' }_
- `comment`
- `flash`

---

## File Types 

> Load plugins for specific file types

- `neodev`: _ft = { 'lua', 'vim' }_
- `rails`: _ft = 'ruby'_
- `markdown-preview`: _ft = 'markdown', cmd = 'MarkdownPreviewToggle'_

> Lazy loading conditions can be _combined_

---

## Links 

- [nvim2k](https://github.com/2KAbhishek/nvim2k)
- [lazy spec](https://github.com/2KAbhishek/nvim2k/blob/main/lua/plugins/list.lua)
- [slides](https://github.com/2KAbhishek/talks/blob/main/the-laziest-neovim.md)

---

# That's All Forks! 

- [GitHub](https://github.com/2KAbhishek)
- [Twitter](https://twitter.com/2KAbhishek)
- [YouTube](https://youtube.com/2KAbhishek)
