# Starship Theme Switcher

A simple setup to easily switch starship themes / profiles. (obv customizable, this repo is just a starting point)

As I just switched to NixOS I made I version for that, if you want it in you nix config: [NixOS starship theme switcher](https://gist.github.com/a3chron/2b7479cb3a256a9590d251c5e66b663a)

<table>
  <tr>
    <td><img src="/assets/green.png" alt="green" /></td>
    <td><img src="/assets/blue.png" alt="blue" /></td>
    <td><img src="/assets/red.png" alt="red" /></td>
  </tr>
</table>

> [!NOTE]
> `starship-theme` only switches the starship config. It can be part in bigger scripts to change the entire system theme if needed.
> For the borders, the gnome extension **Rounded Window Corners Reborn** is used.
> The quick-settings color is set manually too, in the settings.

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

<br />

<p align="center">
 <a href="https://github.com/a3chron/starship-theme-switcher/blob/main/LICENSE"><img src="https://img.shields.io/github/license/a3chron/starship-theme-switcher?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
</p>




