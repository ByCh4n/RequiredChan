<h1 align="center">RequiredChan</h1>

<p align="center">
  <img src="https://github.com/ByCh4n/RequiredChan/actions/workflows/shellcheck.yml/badge.svg" alt="ShellCheck" />
  <img src="https://img.shields.io/github/license/ByCh4n/RequiredChan" alt="License" />
  <img src="https://img.shields.io/github/stars/ByCh4n/RequiredChan?style=social" alt="Stars" />
</p>

A one-command installer that sets up the essential tools you need on a fresh
**Kali Linux** or **Termux** environment. If you are not sure which packages to
install to get started, RequiredChan installs the common set for you in a single
step.

## Features

- Installs a curated baseline of tools with a single menu choice
- Works on **Kali Linux** and **Termux**
- Optional Kali Linux repository update helper
- Simple bilingual (TR/EN) interactive menu

## Requirements

- `bash`
- An `apt`- or `pacman`-based distribution (Kali / Debian / Arch) or Termux
- Root privileges (`sudo`)
- An active internet connection

## Installation

```bash
git clone https://github.com/ByCh4n/RequiredChan
cd RequiredChan
sudo bash reqchan
```

## Usage

Run `sudo bash reqchan` and choose an option from the menu:

| Option | Description |
|--------|-------------|
| `1` | Launch the automatic installer for the required tools |
| `2` | Update Kali Linux repositories (Kali only) |
| `x` | Exit |

## Disclaimer

This project is provided for **educational purposes only** and installs
third-party software on your system. Review what it installs before running it,
and use it only on systems you control. The author accepts no liability for
misuse or any damage caused.

## Author

**Hüseyin Altıntaş — ByCh4n**

- GitHub: [@ByCh4n](https://github.com/ByCh4n)
- LinkedIn: [huseyinaltns](https://www.linkedin.com/in/huseyinaltns/)
- X: [@huseyinaltns](https://x.com/huseyinaltns)

Special thanks to [@lazypwny751](https://github.com/lazypwny751).

## License

Licensed under the [GPL-3.0](LICENSE) license.
