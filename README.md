# rcfiles

dotfiles: bash + vim + git, symlinked by install.sh

Built for my own use; public in case it helps someone.

## Examples

```bash
# configs are symlinked, edit here and it applies everywhere
```

## Highlights

- Sane vim defaults, no plugins required
- Git aliases I actually use daily
- One-command setup: ./install.sh
- Bash prompt with git branch indicator

## Getting started

```bash
git clone <this repo> ~/.dotfiles
cd ~/.dotfiles
./install.sh
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .bashrc
├── .editorconfig
├── .gitignore
├── .vimrc
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
└── install.sh
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT licensed, see LICENSE.
