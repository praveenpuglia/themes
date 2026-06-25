# Soft Themes

Warm, high-contrast, easy-on-the-eyes themes built on a shared palette.

- **Soft Day** — light, warm off-white (`#f6f3ec`) on dark slate (`#2c333d`)
- **Soft Night** — dark, dark slate (`#1c2128`) on soft fog (`#d4dae3`)

## Ghostty

Copy the theme files into your Ghostty themes directory and reference them in `config`:

```sh
cp ghostty/soft-day ghostty/soft-night ~/.config/ghostty/themes/
```

```
theme = dark:soft-night,light:soft-day
```

## VS Code

Symlink (or copy) `vscode/` into your extensions folder, then reload and pick the theme via `Cmd+K Cmd+T`:

```sh
ln -sfn "$PWD/vscode" ~/.vscode/extensions/soft-themes
```

Both themes cover the full workbench color surface, TextMate `tokenColors`, and semantic highlighting.
