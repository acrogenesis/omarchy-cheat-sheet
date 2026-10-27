# Omarchy Printable Hotkeys Cheat Sheet

A compact, printable reference of [Omarchy's hotkeys](https://omarchy.org/manual/hotkeys/)

**Live page:** [https://acrogenesis.com/omarchy-cheat-sheet/](https://acrogenesis.com/omarchy-cheat-sheet/)

## Hotkey sources

Last checked **October 26, 2026** against the [official hotkeys manual](https://omarchy.org/manual/hotkeys/) and Omarchy's `quattro` defaults at [`39d56653d`](https://github.com/omacom/omarchy/tree/39d56653d649312453316f2536fcfb9982f08fb8).

When updating, compare every section with the manual, then check the actual defaults:

- [Desktop bindings](https://github.com/omacom/omarchy/tree/39d56653d649312453316f2536fcfb9982f08fb8/default/hypr/bindings), including optional app and dictation bindings.
- [Keyboard/compose setup](https://github.com/omacom/omarchy/blob/39d56653d649312453316f2536fcfb9982f08fb8/default/hypr/input.lua) and [compose sequences](https://github.com/omacom/omarchy/blob/39d56653d649312453316f2536fcfb9982f08fb8/default/xcompose).
- [Tmux config](https://github.com/omacom/omarchy/blob/39d56653d649312453316f2536fcfb9982f08fb8/config/tmux/tmux.conf), [Ghostty config](https://github.com/omacom/omarchy/blob/39d56653d649312453316f2536fcfb9982f08fb8/config/ghostty/config), and [LazyVim keymaps](https://www.lazyvim.org/keymaps). Ghostty's built-in bindings can be listed with `ghostty +list-keybinds --default`.

The sheet includes source-confirmed shortcuts the manual omits, such as minimizing to the dock, input language switching, select all, and the optional LazyDocker binding. Ghostty's default 10-line split resize conflicts with Omarchy's move-window-to-monitor shortcut; the sheet documents that conflict instead of listing it as an available resize shortcut. Personal overrides and older installations can differ.

After editing, preview both screen and print layouts; the A4 printout should remain two pages with the credit only on the final page.

## Customize

Edit `index.html` directly:

- Add / remove hotkeys: modify or duplicate table rows.
- Adjust print styling: tweak the `@media print` block.

## Contributing

Small fixes / additions welcome—open a PR with a short description of the change.

## License

See `LICENSE` (MIT).
