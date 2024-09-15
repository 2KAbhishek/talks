# Building Neovim Plugins: A Journey from Novice to Pro

**Abhishek Keshri**
Terminal lover, Neovim enthusiast
[GitHub](https://github.com/2kabhishek) | [X](https://x.com/2kabhishek)

---

## Introduction

- **Why Neovim?**
  - Lightweight, highly customizable, Lua-based plugin system
  - Seamless integration with external tools
  - Wide community support

- **Why Plugin Development?**
  - Enhance productivity, Automating tasks
  - Customize your workflow, Custom commands and shortcuts
  - Integration with third-party services
  - Contribute to the ecosystem

---

## Plugin Development: Getting Started

- **Step 1: The Development Environment**
  - Lazy.nvim and Lua
  - A ready to use plugin template: [template.nvim](https://github.com/2kabhishek/template.nvim)

- **Demo:**
  - Overview of a plugin's directory structure

```bash
     .
    ├──  doc
    │  └──  images
    ├──  lua
    │  ├──  template
    │  └──  template.lua
    ├──  plugin
    │  └──  template.lua
    ├──  tests
    │  ├──  template
    │  └──  init.lua
    ├──  .github
    │  ├──  ISSUE_TEMPLATE
    │  └──  workflows
    ├──  LICENSE
    ├──  Makefile
    ├──  .gitignore
    ├──  README.md
    └──  .stylua.toml
```

---

## Your First Plugin

- **Step 2: Your First Plugin**
  - How do I?
    - Define a command
    - Map keys to functionality
    - Add user configuration

---

## Best Practices

- Separation of logic: commands vs config
- Avoid polluting global scope
- Use Neovim’s API effectively

---

## Building Advanced Plugins

- **Advanced Features:**
  - Asynchronous APIs (for background tasks)
  - Integration with external tools (Git, Docker, etc.)
  - Using Treesitter and LSP for powerful editing capabilities

- **Demo:**
  - Showcase a plugin with real-world functionality (e.g., integrating with a CI tool or automating a workflow)
---

## Publishing & Sharing Plugins

- **Step-by-Step:**
  - Publishing on GitHub
  - Adding to [awesome-neovim](https://github.com/rockerBOO/awesome-neovim)
  - Writing documentation
  - Encouraging contributions and maintaining your plugin

---

## Tips for Aspiring Plugin Authors

- **Start Simple:** Don’t aim for perfection, begin with a small useful feature.
- **Iterate:** Learn by improving your plugin based on user feedback.
- **Collaborate:** Leverage the community for ideas and contributions.
- **Have Fun:** Enjoy the process of learning and contributing!

---

## Q&A

- **Let’s Talk:**
  - Questions about plugin development?
  - Challenges in starting out?
  - Ideas you want to explore?
    - Are there any plugins you want to build?

---

## Thank You!

- **Closing Remarks:**
  - Let's build more plugins together!

- Feel free to reach out for help or collaboration: [All my links](https://2kabhishek.github.io/links)
