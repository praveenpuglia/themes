# Soft Themes

High-contrast, easy-on-the-eyes themes built on a shared palette.

- **Soft Day** — light, near-neutral soft-white (`#f4f4f0`) on dark slate (`#2c333d`)
- **Soft Night** — dark, dark slate (`#1c2128`) on soft fog (`#d4dae3`)

Each palette below drives the Ghostty, VS Code, and Zed versions of that theme.

```
soft/
  light/   ghostty/  vscode/  zed/  soft-day-palette.svg
  dark/    ghostty/  vscode/  zed/  soft-night-palette.svg
```

### Soft Day

![Soft Day palette](light/soft-day-palette.svg)

### Soft Night

![Soft Night palette](dark/soft-night-palette.svg)

## Ghostty

Copy the theme files into your Ghostty themes directory and reference them in `config`:

```sh
cp light/ghostty/soft-day dark/ghostty/soft-night ~/.config/ghostty/themes/
```

```
theme = dark:soft-night,light:soft-day
```

## VS Code

Each variant is a standalone extension. Symlink (or copy) the one(s) you want into your extensions folder, then reload and pick the theme via `Cmd+K Cmd+T`:

```sh
ln -sfn "$PWD/light/vscode" ~/.vscode/extensions/soft-day
ln -sfn "$PWD/dark/vscode"  ~/.vscode/extensions/soft-night
```

Both cover the full workbench color surface, TextMate `tokenColors`, and semantic highlighting.

## Zed

Copy (or symlink) the theme files into your Zed themes directory:

```sh
ln -sfn "$PWD/dark/zed/soft-night.json" ~/.config/zed/themes/soft-night.json
ln -sfn "$PWD/light/zed/soft-day.json" ~/.config/zed/themes/soft-day.json
```

Then select **Soft Night** or **Soft Day** from the theme picker (`Cmd+K Cmd+T`).
