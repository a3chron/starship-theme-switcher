# Starship Theme Switcher

A simple setup to easily switch starship themes / profiles. (obv customizable, this repo is just a starting point)

You can use following command to switch predifined themes:
```bash
starship-theme blue
```

Maybe a lil bit inefficient, it just has a themes folder in `./config`, with all starship configs, 
and copies the selected theme to the starship config location.

# Contributing

Contributions are welcome, please rember to use conventional commits :)

# Usage

Put the `starship-theme` in your bin directory, make it executable, basically done.
You may have to adjust certain paths, in case you don't use the same as me...

# Todos

- [ ] move themes in a extra /themes direcory
- [ ] maybe extra seperation, e.g. in themes dir again other directories, and then `switch catppuccin:blue` or similar (to make it easier adding more themes)
- [ ] automate some parts of the switch script, i.e. check the themes direcory for possible themes, don't hardcode
- [ ] add images / preview / gif

