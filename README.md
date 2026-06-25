# Ubuntu Mono

A customized build of the Ubuntu Mono monospaced typeface.

## Fonts

| File | Style |
| --- | --- |
| `UbuntuMono-Regular.ttf` | Regular |
| `UbuntuMono-Bold.ttf` | Bold |
| `UbuntuMono-Italic.ttf` | Italic |
| `UbuntuMono-BoldItalic.ttf` | Bold Italic |

## Installation

### Linux

```bash
mkdir -p ~/.local/share/fonts
cp *.ttf ~/.local/share/fonts/
fc-cache -f -v
```

### macOS

Double-click each `.ttf` file and click **Install Font**, or copy them to `~/Library/Fonts/`.

### Windows

Select the `.ttf` files, right-click, and choose **Install** (or **Install for all users**).

## License

Ubuntu Mono is distributed under the [Ubuntu Font Licence 1.0](https://ubuntu.com/legal/font-licence).
