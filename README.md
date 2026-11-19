# jgnav.github.io
Welcome to [Juan Gutiérrez's website](https://jgnav.github.io/)!

## Paper pages

Paper pages (e.g. [`panc/`](https://jgnav.github.io/panc/)) are compiled from
the LaTeX sources with [`tex_to_html/`](tex_to_html/README.md):

```bash
python3 tex_to_html/tex_to_html.py path/to/paper/main.tex --out panc/
```

Requires `latexml` (`sudo apt install latexml`); metadata goes in a
`paper.json` next to `main.tex`.

## Credits

- Template: adapted from [Jon Barron's website](https://github.com/jonbarron/jonbarron.github.io), including its `tex_to_html` paper compiler.
- Colours: GitHub-style light theme; [Gruvbox](https://github.com/morhetz/gruvbox) dark mode.
- Fonts: [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) and [JetBrains Mono](https://www.jetbrains.com/lp/mono/).
