# Homebrew tap for mop

**English** | [Русский](README.md)

Official [Homebrew](https://brew.sh) tap for [mop](https://github.com/thothlab/macos-mop) — a fast macOS system cleaner CLI utility.

## Installation

```bash
brew tap thothlab/macos-mop
brew install mop
```

Or in a single command:

```bash
brew install thothlab/macos-mop/mop
```

## Usage

```bash
# Preview what can be cleaned (dry run, nothing deleted)
mop clean --dry-run --all

# Clean all categories
mop clean --all

# Completely uninstall an app with all its files
mop uninstall "Slack"

# Analyze disk space usage
mop analyze ~/Documents

# Remove build artifacts (node_modules, target, .build...)
mop purge ~/Projects

# System health overview
mop status
```

## Upgrade

```bash
brew update
brew upgrade mop
```

## Uninstall

```bash
brew uninstall mop
brew untap thothlab/macos-mop
```

## Links

- [Source code](https://github.com/thothlab/macos-mop)
- [Releases](https://github.com/thothlab/macos-mop/releases)
- [Report an issue](https://github.com/thothlab/macos-mop/issues)

## License

MIT
