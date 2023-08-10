# .SpaceVim.d

My SpaceVim configuration with the following language layers enabled:
- html
- python

# Installation

## Details for HTML Layer (on Arch)

First install `npm` and `nodejs`:

```bash
sudo pacman -S npm nodejs
```

Then lsp for HTML:

```bash
sudo npm install --global vscode-html-languageserver-bin
```

## Details for Python Layer (on Arch)

Installation of nice to have python modules:

```bash
sudo pacman -S python-pylint    \
               yapf             \
               python-isort     \
               python-coverage
```

If not already done, installation of `yay` to simplify access to [AUR](https://aur.archlinux.org/)

```bash
pacman -S --needed git base-devel && git clone https://aur.archlinux.org/yay.git && cd yay && makepkg -si
```

Installation of modules available only on [AUR](https://aur.archlinux.org/):

```bash
yay -S python-autoflake
```

Then `npm` and `nodejs` (if not already done):

```bash
sudo pacman -S npm nodejs
```

And pyright languageserver for python:

```bash
sudo npm install -g pyright
```

