<!-- lint ignore awesome-git-repo-age -->

# Awesome WezTerm with stars

<img src="https://raw.githubusercontent.com/wez/wezterm/main/assets/icon/wezterm-icon.svg" align="right" width="144" />

> Collections of awesome WezTerm plugins. [Plugin Guide](https://github.com/wezterm/wezterm/blob/main/docs/config/plugins.md) ⭐ 28,525 | 🐛 1,823 | 🌐 Rust | 📅 2026-08-24. Found something cool? Please [contribute](CONTRIBUTING.md)!

[WezTerm](https://wezfurlong.org/wezterm/) is a powerful cross-platform terminal emulator and multiplexer written by [@wez](https://github.com/wez) and implemented in [Rust](https://www.rust-lang.org).

To enhance your WezTerm configuration experience:

* [DrKJeff16/wezterm-types](https://github.com/DrKJeff16/wezterm-types) ⭐ 220 | 🐛 2 | 🌐 Lua | 📅 2026-08-22 - WezTerm type annotations that can be added as a completion source in your editor to provide code assistance when working with WezTerm's Lua API. Includes community plugins support.

## Contents

* [AI](#ai)
* [Keybinding](#keybinding)
* [Media](#media)
* [Neovim](#neovim)
* [Panes](#panes)
* [Session](#session)
* [Tab bar](#tab-bar)
* [Themes](#themes)
* [Utility](#utility)

## AI

* [Eric162/wezterm-agent-deck](https://github.com/Eric162/wezterm-agent-deck) ⭐ 74 | 🐛 1 | 🌐 Lua | 📅 2026-03-26 - Monitors AI coding agents, shows status dots in tabs and notifications when agents need attention.
* [Michal1993r/ai-helper.wezterm](https://github.com/Michal1993r/ai-helper.wezterm/tree/master) ⭐ 38 | 🐛 1 | 🌐 Lua | 📅 2026-03-13 - Ask AI for CLI help with LM Studio or Google Gemini.
* [dimao/ai-commander.wezterm](https://github.com/dimao/ai-commander.wezterm) ⭐ 11 | 🐛 2 | 🌐 Lua | 📅 2026-05-09 - Generate and select bash commands based on natural language prompts.
* [M-Marbouh/agent-quota.wezterm](https://github.com/M-Marbouh/agent-quota.wezterm) ⭐ 5 | 🐛 0 | 🌐 Lua | 📅 2026-08-21 - Shows Claude and Codex quota usage in the status bar with reset countdowns, process-aware states, and shared caching.
* [EdenGibson/wezterm-quota-limit](https://github.com/EdenGibson/wezterm-quota-limit) ⭐ 3 | 🐛 0 | 🌐 Lua | 📅 2026-06-21 - Shows Claude API usage quota in the status bar with color-coded thresholds and automatic token refresh.

## Keybinding

* [MLFlexer/modal.wezterm](https://github.com/MLFlexer/modal.wezterm) ⚠️ Archived - Predefined Vim-like modal keybindings with a good looking UI.
* [sei40kr/wez-tmux](https://github.com/sei40kr/wez-tmux) ⭐ 55 | 🐛 2 | 🌐 Lua | 📅 2025-11-03 - Ported tmux keybindings.
* [abidibo/wezterm-cmdpicker](https://github.com/abidibo/wezterm-cmdpicker) ⭐ 17 | 🐛 0 | 🌐 Lua | 📅 2026-05-25 - Add a command-palette-style fuzzy picker for keybindings. Press a trigger key to search and execute any keybinding — user-defined, config, or WezTerm defaults.
* [sei40kr/wez-pain-control](https://github.com/sei40kr/wez-pain-control?tab=readme-ov-file) ⭐ 10 | 🐛 0 | 🌐 Lua | 📅 2023-11-21 - Pane control keybindings like tmux-pain-control.
* [annie444/sync-panes.wez](https://github.com/annie444/sync-panes.wez) ⭐ 6 | 🐛 3 | 🌐 Lua | 📅 2026-07-09 - Mirrors your keystrokes to every pane in the active tab — the equivalent of tmux's `synchronize-panes`.
* [sravioli/chord.wz](https://github.com/sravioli/chord.wz) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - Vim-style key notation, modal key tables, and hint bars.
* [selectnull/pinned-tabs.wezterm](https://github.com/selectnull/pinned-tabs.wezterm) ⭐ 4 | 🐛 0 | 🌐 Lua | 📅 2025-08-16 - Lets you assign a key binding to a specific tab.
* [KawaiiSelbst/nu\_utf8\_hack.wez](https://github.com/KawaiiSelbst/nu_utf8_hack.wez) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2026-01-11 - Rough hack for correct handling utf8 symbols with `SHIFT` key with `kitty-keyboard-protocol` for users of nushell.
* [KawaiiSelbst/keys\_bypass.wez](https://github.com/KawaiiSelbst/keys_bypass.wez) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2026-07-15 - Bypasses WezTerm shortcuts to send keys to the foreground process (e.g., Zellij or tmux).

## Media

* [xarvex/presentation.wez](https://github.com/xarvex/presentation.wez) ⭐ 19 | 🐛 0 | 🌐 Lua | 📅 2024-09-12 - Rather simple presentation mode toggle.

## Neovim

* [mrjones2014/smart-splits.nvim](https://github.com/mrjones2014/smart-splits.nvim) ⭐ 1,713 | 🐛 22 | 🌐 Lua | 📅 2026-08-22 - Provides an addon for seamless pane navigation between Neovim and the WezTerm MUX.
* [winter-again/wezterm-config.nvim](https://github.com/winter-again/wezterm-config.nvim) ⭐ 72 | 🐛 2 | 🌐 Lua | 📅 2026-04-01 - Interact with the WezTerm configuration directly from Neovim.

## Panes

* [ChrisGVE/pivot\_panes.wezterm](https://github.com/ChrisGVE/pivot_panes.wezterm) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2026-03-06 - Toggle pane orientation between horizontal and vertical splits.
* [bad-noodles/stack.wez](https://github.com/bad-noodles/stack.wez) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2025-11-23 - Stacked pane mode, work with multiple panes but see only one at a time.

## Session

* [MLFlexer/smart\_workspace\_switcher.wezterm](https://github.com/MLFlexer/smart_workspace_switcher.wezterm) ⚠️ Archived - Switch between workspaces with fuzzy finding and `zoxide`.
* [mikkasendke/sessionizer.wezterm](https://github.com/mikkasendke/sessionizer.wezterm) ⭐ 96 | 🐛 1 | 🌐 Lua | 📅 2025-07-05 - Opening Git repositories as their own WezTerm workspaces using `fd`.
* [DavidRR-F/quick\_domains.wezterm](https://github.com/DavidRR-F/quick_domains.wezterm) ⭐ 28 | 🐛 4 | 🌐 Lua | 📅 2026-02-01 - Faster way to search and attach to (SSH) domains.
* [abidibo/wezterm-sessions](https://github.com/abidibo/wezterm-sessions) ⭐ 27 | 🐛 0 | 🌐 Lua | 📅 2026-05-25 - Save and restore sessions.
* [vieitesss/workspacesionizer.wezterm](https://github.com/vieitesss/workspacesionizer.wezterm) ⭐ 17 | 🐛 0 | 🌐 Lua | 📅 2026-03-03 - Blazingly fast workspace chooser inspired by `tmux-sessionizer`.
* [isseii10/workspace-picker.wezterm](https://github.com/isseii10/workspace-picker.wezterm) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2026-05-17 - Workspace switcher with `zoxide` integration.
* [ryanmsnyder/workspace-manager.wezterm](https://github.com/ryanmsnyder/workspace-manager.wezterm) ⭐ 7 | 🐛 5 | 🌐 Lua | 📅 2026-04-24 - Navigate projects effortlessly with smart workspace switching and keyboard-driven navigation.
* [JuanraCM/wsinit.wezterm](https://github.com/JuanraCM/wsinit.wezterm) ⭐ 6 | 🐛 0 | 🌐 Lua | 📅 2026-03-02 - A simple and flexible way to manage and initialize workspace configurations.
* [StephenGemin/resurrect.wezterm](https://github.com/StephenGemin/resurrect.wezterm) ⭐ 0 | 🐛 2 | 🌐 Lua | 📅 2026-07-14 - Save and restore the state of workspaces, windows, tabs and panes.
* [srackham/tabsets.wezterm](https://github.com/srackham/tabsets.wezterm) ⭐ 0 | 🐛 0 | 🌐 Lua | 📅 2026-05-16 - Load, save, rename and delete named sets of tabs.

## Tab bar

* [michaelbrusegard/tabline.wez](https://github.com/michaelbrusegard/tabline.wez) ⭐ 303 | 🐛 2 | 🌐 Lua | 📅 2026-07-23 - A versatile and easy to use retro tab bar with the `lualine.nvim` configuration format.
* [adriankarlen/bar.wezterm](https://github.com/adriankarlen/bar.wezterm) ⭐ 238 | 🐛 1 | 🌐 Lua | 📅 2026-04-15 - A configurable tab bar with batteries included.
* [yriveiro/wezterm-tabs](https://github.com/yriveiro/wezterm-tabs) ⭐ 30 | 🐛 1 | 🌐 Lua | 📅 2026-08-14 - Configurable tabs for the retro tab bar.
* [yriveiro/wezterm-status](https://github.com/yriveiro/wezterm-status) ⭐ 25 | 🐛 0 | 🌐 Lua | 📅 2026-03-23 - Configurable status for the retro tab bar.
* [pro-vi/wezterm-attention](https://github.com/pro-vi/wezterm-attention) ⭐ 18 | 🐛 0 | 🌐 Lua | 📅 2026-08-24 - Turns your tab bar into a notification system with colored tab indicators.
* [rootiest/battery.wez](https://github.com/rootiest/battery.wez) ⭐ 10 | 🐛 0 | 🌐 Lua | 📅 2024-10-07 - A colorful and fancy battery component for the retro tab bar.

## Themes

* [neapsix/wezterm](https://github.com/neapsix/wezterm) ⭐ 81 | 🐛 0 | 🌐 Lua | 📅 2024-05-11 - Rosé Pine theme, all natural pine, faux fur and a bit of soho vibes.
* [koh-sh/wezterm-theme-rotator](https://github.com/koh-sh/wezterm-theme-rotator) ⭐ 9 | 🐛 0 | 🌐 Lua | 📅 2025-03-23 - Cycle through built-in themes using keyboard shortcuts.
* [sravioli/kanagawa.wz](https://github.com/sravioli/kanagawa.wz) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - Kanagawa.nvim color schemes with Wave, Dragon, and Lotus variants.
* [willytop8/Wezterm-Window-Tint](https://github.com/willytop8/Wezterm-Window-Tint) ⭐ 3 | 🐛 0 | 🌐 Lua | 📅 2026-06-29 - Color the window frame, tab bar, and status badge by the active pane's Git root.
* [Tomauskasz/electric-control-room.wez](https://github.com/Tomauskasz/electric-control-room.wez) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2026-07-16 - Animated electric control-room theme with layered APNG background effects.

## Utility

* [zsh-sage/toggle\_terminal.wez](https://github.com/zsh-sage/toggle_terminal.wez) ⭐ 23 | 🐛 0 | 🌐 Lua | 📅 2025-10-22 - An easy-to-use toggleable terminal window.
* [ChrisGVE/listeners.wezterm](https://github.com/ChrisGVE/listeners.wezterm) ⭐ 13 | 🐛 0 | 🌐 Lua | 📅 2026-05-26 - Enables enhanced event listener capabilities with persistent state management.
* [ChrisGVE/lib.wezterm](https://github.com/ChrisGVE/lib.wezterm) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2026-05-26 - A library of common utility functions for plugin developers.
* [quantonganh/quickselect.wezterm](https://github.com/quantonganh/quickselect.wezterm) ⭐ 8 | 🐛 0 | 🌐 Lua | 📅 2025-12-13 - Jump to the build error by opening them in Helix.
* [ChrisGVE/dev.wezterm](https://github.com/ChrisGVE/dev.wezterm) ⭐ 7 | 🐛 1 | 🌐 Lua | 📅 2026-05-26 - Location resolver for development and deployment of a plugin.
* [usrivastava92/widgets.wez](https://github.com/usrivastava92/widgets.wez) ⭐ 7 | 🐛 0 | 🌐 Lua | 📅 2026-06-29 - Cross-platform status bar widgets for CPU, RAM, battery, network, and disk on macOS, Linux, and Windows.
* [aureolebigben/wezterm-cmd-sender](https://github.com/aureolebigben/wezterm-cmd-sender) ⭐ 6 | 🐛 0 | 🌐 Lua | 📅 2026-04-19 - Send commands to multiple panes.
* [dfsramos/wezterm-sync](https://github.com/dfsramos/wezterm-sync) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-05-11 - Sync your config across machines via a private GitHub Gist, with zero external dependencies.
* [sravioli/lantern.wz](https://github.com/sravioli/lantern.wz) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - Selector framework for colorschemes, fonts, GPU adapters, window appearance, and custom config presets.
* [sravioli/memo.wz](https://github.com/sravioli/memo.wz) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - Memoization, caching, and persistent state management.
* [sravioli/ribbon.wz](https://github.com/sravioli/ribbon.wz) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - Builds styled text segments for status bars, tab titles, and selector previews.
* [sravioli/warp.wz](https://github.com/sravioli/warp.wz) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - General-purpose utility library with string, table, list, path, and filesystem helpers.
* [btrachey/wezterm-replay](https://github.com/btrachey/wezterm-replay) ⭐ 2 | 🐛 0 | 🌐 Lua | 📅 2025-09-18 - Parse command output and get URLs, shell commands, etc. pasted into your next prompt.
* [sravioli/log.wz](https://github.com/sravioli/log.wz) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - Tagged logging library with pluggable sinks and severity thresholds.
* [sravioli/sigil.wz](https://github.com/sravioli/sigil.wz) ⭐ 1 | 🐛 0 | 🌐 Lua | 📅 2026-05-14 - Icon and identity-color registry for processes, tools, and UI labels.
* [lilaqua/tunicodes](https://gitlab.com/lilaqua/tunicodes) - Insert Unicode characters via their codepoints.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
