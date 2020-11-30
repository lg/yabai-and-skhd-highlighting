# yabai+skhd Highlighter

![screenshot](screenshot.png)
_(color theme is Afterglow Remastered)_

Install this extension to do VSCode syntax highlighting on `yabairc` and `skhdrc` files (for [yabai](https://github.com/koekeishiya/yabai) and [skhd](https://github.com/koekeishiya/skhd)). This should make it way easier to read and modify your configs. Note I'm not the guy who made skhd or yabai, I just like colors.

## Installing from source

If you're getting this extension via source code, put this directory into your `~/.vscode/extensions`. Then start VSCode and open up your `.yabairc` and `.skhdrc` files. Colors should ensue!

## Todo

- This is way too colorful, need to tone it down dramatically
- Same-line comments in both files don't highlight correctly right now
- Similar to the last point, end properly with &&, ;, |, and all the other shell tokens
- Fix patterns like `yabai -m space 5 --label abc` and `yabai -m space --label abc` (without the num)
- Support other yabai flags like `--load-sa`
- For skhd, use the full-on tokenized stuff Asmund [details](https://github.com/koekeishiya/skhd#configuration)
- Write some autocompletions based on https://github.com/koekeishiya/yabai/blob/master/src/message.c
- Write tests (haha)

## Changelog

### 1.0.0 (Nov 29, 2020)

- Initial release with both yabairc and skhdrc highlighting