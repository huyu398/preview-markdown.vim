# preview-markdown.vim
This is vim plugin that can preview markdown in Vim terminal.

![](https://i.imgur.com/ME5HBWP.png)

## Requirements
- [MichaelMure/mdr](https://github.com/MichaelMure/mdr) or specified markdown parser

## Installation
e.g dein.vim

```toml
[[plugin]]
repo = 'skanehira/preview-markdown.vim'
```

## Usage
```vim
:PreviewMarkdown
```

## Options
| option                        | description                                               |
|-------------------------------|-----------------------------------------------------------|
| `g:preview_markdown_vertical` | open window vartical when value is `1`                    |
| `g:preview_markdown_parser`   | use specified command to parse markdown, default is `mdr` |

## Markdown parser
- [MichaelMure/mdr](https://github.com/MichaelMure/mdr)
- [glow](https://github.com/charmbracelet/glow)
- [mdcat](https://github.com/lunaryorn/mdcat)

## Author
skanehira
