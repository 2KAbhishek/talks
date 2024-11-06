# Building Neovim Plugins: A Journey from Novice to Pro

**Abhishek Keshri**

> Terminal lover, Developer tooling enthusiast

[GitHub](https://github.com/2kabhishek) | [X](https://x.com/2kabhishek)

- I work at Incubyte
- From a small town in India, Rampurhat
- Worked remotely for all my professional career (4 Years)

---

## My (Neo)Vim Journey

- Vim (2018-2021) -> Neovim (2021-)

### Plugins I've Built

- co-author.nvim: Add git co-authors
- nerdy.nvim: Nerd glyph finder
- tdo.nvim: Notes and todos
- termim.nvim: Improved terminal integration
- markit.nvim: Simpler marks
- octohub.nvim: Manage GitHub repos easily
- exercism.nvim: Exercism.io integration

---

## Why Plugin Development?

- Enhance productivity, Automating tasks
- Customize your workflow, Custom commands and shortcuts
- Integration with third-party services
- Contribute to the ecosystem

> At the end of this talk, I'd like you to try building plugins

---

## Plugin Development: Pre-requisites

**The Development Environment**

- Lazy.nvim and Lua
- A ready to use plugin template: [template.nvim](https://github.com/2kabhishek/template.nvim)
- Overview of a plugin's directory structure

---

## Your First Plugin

What kind of things can you do with a plugin?

- Define a command
- Map keys to functionality
- Add user configuration

> What do you want to build?

---

## Building Advanced Plugins

**Advanced Features:**

- Asynchronous APIs (for background tasks)
- Integration with external tools (Git, Docker, etc.)
- Using Treesitter and LSP for powerful editing capabilities

> plenary.nvim, utils.nvim

---

## Best Practices

- Respect user configuration, provide sensible defaults, and allow customization
- Document everything, all commands, configurations, and keybindings
- Test all behavior, use CI to automate testing
- Mind the performance, minimize blocking operations, use async APIs
- Separation of logic, use modules for different functionalities
- Use Neovim’s API effectively

---

## Publishing & Sharing Plugins

- Publishing on GitHub
- Adding to [awesome-neovim](https://github.com/rockerBOO/awesome-neovim)
- Encourage contributions, actively maintain your plugin

---

## Tips for Aspiring Plugin Authors

- **Start Simple:** Don’t aim for perfection, begin with a small useful feature.
- **Iterate:** Learn by improving your plugin based on user feedback.
- **Collaborate:** Leverage the community for ideas and contributions.
- **Have Fun:** Enjoy the process of learning and contributing

---

## Thank You

**Let's build more plugins together**

Feel free to reach out for questions, ideas or just to chat.

[talk slides](https://github.com/2kabhishek/talks/blob/main/building-neovim-plugins.md)
