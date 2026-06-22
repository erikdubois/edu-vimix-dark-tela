<p align="center">
  <img src="kiro.jpg" alt="Kiro" width="220" />
</p>

# kiro-vimix-dark-tela

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
sudo pacman -S kiro-vimix-dark-tela
```

### Manual

```bash
git clone https://github.com/kirodubes/kiro-vimix-dark-tela.git
cd kiro-vimix-dark-tela
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

<!-- KIRO-FUNDING-FOOTER:START — managed by Kiro-HQ/cascade-readme-footer.sh -->
## Help fund Kiro

Everything I build here stays free and open — always. If Kiro or any of these
tools have ever saved you time or taught you something, a small monthly
contribution helps keep the work going. Donations target break-even, nothing
more — the core always stays free for everyone.

- GitHub Sponsors: https://github.com/sponsors/erikdubois
- Patreon: https://www.patreon.com/c/kiroproject
- YouTube memberships: https://www.youtube.com/@ErikDubois/join
- Ko-fi: https://ko-fi.com/erikdubois
- PayPal: https://www.paypal.me/erikdubois
<!-- KIRO-FUNDING-FOOTER:END -->

## License

See [LICENSE](./LICENSE).
