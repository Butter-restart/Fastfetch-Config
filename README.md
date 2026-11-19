# fastfetch-config

my fastfetch config for arch + kde plasma.

put a "Tess" banner at the top, kept a braille ghost logo (`ghost.txt`), and set up sectioned boxes with red keys, progress bars, and pacman/ghost colors at the bottom. also still have my older logo files (`FUCK YEAAAAA.png`, `shut.png`, `sc.txt`) around if i want to swap back.

## setup

drop the files into `~/.config/fastfetch/`:

```bash
mkdir -p ~/.config/fastfetch
cp config.jsonc ghost.txt DESCRIPTION.txt ~/.config/fastfetch/
```

then run:

```bash
fastfetch
```

## notes / things to keep in mind

- you'll want a nerd font set in your terminal or some of the icons/lines will look like boxes.
- if you swap the logo in `config.jsonc`, keep the path pointing to `~/.config/fastfetch/...` so it finds the file no matter where you run `fastfetch` from.
- tweak colors (`38;2;...`) or modules in `config.jsonc` whenever you feel like changing how it looks.# Fastfetch-Config
