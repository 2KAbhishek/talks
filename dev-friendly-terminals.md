# Dev Friendly Terminals

**Abhishek Keshri**

Terminal lover, tooling enthusiast

---

## Things we will cover

- Configuration: aliases, functions, and dotfiles
- Informational prompt - [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh), [Powerlevel10k](https://github.com/romkatv/powerlevel10k) / [Oh My Posh](https://github.com/JanDeDobbeleer/oh-my-posh)
- Directory jumping - [zoxide](https://github.com/ajeetdsouza/zoxide)
- Fuzzy finding - [fzf](https://github.com/junegunn/fzf)
- The best git experience - [lazygit](https://github.com/jesseduffield/lazygit)
- Terminal multiplexer - [tmux](https://github.com/tmux/tmux)
- Runtime management - [mise](https://github.com/misejs/mise)
- Getting help on the terminal - [tldr](https://github.com/tldr-pages/tldr)
- A better ls - [eza](https://github.com/eza-community/eza)
- Searching - [ripgrep](https://github.com/BurntSushi/ripgrep)
- A better cat - [bat](https://github.com/sharkdp/bat)
- A better diff - [delta](https://github.com/dandavison/delta)

---

### **Configuration: Aliases, Functions, and Dotfiles**

- **Aliases**: Shortcuts for frequently used commands
  Example: `alias ll='ls -la'`

- **Functions**: Custom logic encapsulated into reusable commands
  Example:

  ```bash
  function mkcd() {
    mkdir -p "$1" && cd "$1"
  }
  ```

- **Dotfiles**: Configuration files for customizing shell behavior
  Example: `.zshrc`, `.bashrc`, `.vimrc`

- **Version control**: Manage dotfiles in a Git repository for portability
  Example: `git clone your-dotfiles-repo ~/.dotfiles`

---

### **Informational Prompt - Powerlevel10k / Oh My Posh**

- Customizable, fast, and minimalistic shell prompts
- Displays Git status, exit codes, time, and more in real-time
- Works with Zsh (Powerlevel10k) and PowerShell (Oh My Posh)
- Improves productivity by showing relevant info in the prompt

---

### **Directory Jumping - Zoxide**

- Smart navigation based on frequency and recency
- Quick and efficient directory switching with minimal keystrokes
- Works across platforms, including Windows, Linux, and macOS
- Integrates with `fzf` for fuzzy searching directories

---

### **Fuzzy Finding - Fzf**

- Interactive fuzzy search for files, commands, and more
- Works seamlessly with other CLI tools (e.g., `git`, `ls`)
- Customizable keybindings for faster workflows
- Increases efficiency in searching large directories or history

---

### **The Best Git Experience - Lazygit**

- Simplified Git management via a terminal UI
- Easy access to commits, branches, and diffs
- Minimal learning curve for powerful Git workflows
- Boosts productivity by reducing manual Git commands

---

### **Terminal Multiplexer - Tmux**

- Splits terminal into multiple panes and sessions
- Persistent sessions that can survive SSH disconnects
- Customize layouts for specific tasks or workflows
- Enhances multitasking and session management in the terminal

---

### **Runtime Management - Mise**

- Simplifies switching between different versions of tools (e.g., Node, Python)
- Manages environments per project or globally
- Allows seamless integration with various runtime managers (asdf, pyenv, etc.)
- Reduces version conflicts and ensures consistent runtime environments

---

### **Getting Help on the Terminal - Tldr**

- Simplified and community-driven man pages
- Provides concise examples for common commands
- Helps reduce time spent looking up command usage
- Covers a wide range of common Unix commands

---

### **A Better `ls` - Exa**

- Modern replacement for `ls`, with more features
- Git-aware file listings with color-coded output
- Supports tree view and extended file attributes
- Makes file exploration more informative and user-friendly

---

### **Searching - Ripgrep**

- Blazing-fast file searching across directories and files
- Recursively searches large codebases, even hidden files
- Grep-compatible, integrates with `fzf` for interactive searching
- Outperforms traditional `grep` in speed and flexibility

---

### **A Better `cat` - Bat**

- Enhanced `cat` with syntax highlighting
- Git integration to show changes inline
- Displays line numbers and works with various file types
- Makes file viewing more readable, especially for code

---

### **A Better Diff - Delta**

- Improves `git diff` with syntax highlighting and better formatting
- Displays diffs in a more readable, colorful format
- Collapses unchanged code, highlighting only what's necessary
- Provides a clear overview of code changes, boosting review speed

---

### **Conclusion**

For more tools and tips, check out [Terminal Trove](https://terminaltrove.com/)

My workflows and configs:

- [dots2k](https://github.com/2kabhishek/dots2k) for Linux
- [mac2k](https://github.com/2kabhishek/mac2k) for macOS
- [win2k](https://github.com/2kabhishek/win2k) for Windows

