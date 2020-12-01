# yabai+skhd Highlighter

![screenshot](screenshot.png)
_(color theme is Afterglow Remastered)_

Install this extension to do VSCode syntax highlighting on `yabairc` and `skhdrc` files (for [yabai](https://github.com/koekeishiya/yabai) and [skhd](https://github.com/koekeishiya/skhd)). This should make it way easier to read and modify your configs. Note I'm not the guy who made skhd or yabai, I just like colors.

- yabai configuration taken from here: https://github.com/koekeishiya/yabai/blob/master/doc/yabai.asciidoc
- skhd configuration loosly based on tokenization from here: https://github.com/koekeishiya/skhd#configuration

## Installing from source

If you're getting this extension via source code, put this directory into your `~/.vscode/extensions`. Then start VSCode and open up your `.yabairc` and `.skhdrc` files. Colors should ensue!

## Todo

- This is way too colorful, need to tone it down dramatically
- Figure out why action= doesnt highlight properly when going recursive
- Support other yabai flags like `--load-sa`
- Rename this project to something consistent
- For skhd, validate this implemention with the tokenization detailed [here](https://github.com/koekeishiya/skhd#configuration)
- Write some autocompletions based on https://github.com/koekeishiya/yabai/blob/master/src/message.c and https://github.com/koekeishiya/yabai/blob/master/doc/yabai.asciidoc
- Write tests (haha)

## Changelog

### 1.0.0 (Nov 30, 2020)

- Initial release with both yabairc and skhdrc highlighting