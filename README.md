# ALRRRIGGGGTTT!!!

so I put a "Tess" banner at the top, kept a ghost logo (`ghost.txt`) cuz like why not, and set up sectioned boxes with red keys, progress bars, and pacman colors at the bottom.

## SO YOU WANNA USE THIS EH 

drop the files into `~/.config/fastfetch/`:
if you dont have that directory (peasant) 
then 

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
