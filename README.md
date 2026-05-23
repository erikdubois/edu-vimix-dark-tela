<p align="center">
  <img src="kiro.jpg" alt="Kiro" width="220" />
</p>

# edu-vimix-dark-tela

Hybrid icon theme: the [Vimix](https://github.com/vinceliuice/vimix-icon-theme) dark icon set with selected folder icons swapped in from the [Tela](https://github.com/vinceliuice/Tela-icon-theme) family. Part of the `~/EDU/` icon-theme series.

## What's in this repo

- `usr/share/icons/` — the icon theme assets.
- `setup.sh`, `up.sh` — standard EDU bash scaffold.

## Installation

### From `nemesis_repo` (recommended)

```ini
[nemesis_repo]
SigLevel = Never
Server = https://erikdubois.github.io/$repo/$arch
```

```bash
sudo pacman -Syu
sudo pacman -S edu-vimix-dark-tela
```

### Manual

```bash
git clone https://github.com/erikdubois/edu-vimix-dark-tela.git
cd edu-vimix-dark-tela
sudo cp -r usr/share/icons/. /usr/share/icons/
sudo gtk-update-icon-cache -f /usr/share/icons/<theme-folder>
```

### Activate

```bash
gsettings set org.gnome.desktop.interface icon-theme "<theme-folder-name>"
```

## Websites

Information : https://erikdubois.be

## Social Media

Youtube : https://www.youtube.com/erikdubois

## License

See [LICENSE](./LICENSE).
