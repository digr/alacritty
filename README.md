# Alacritty with tmux configuration on macOS.

### Setup

`brew install cask alacritty`

`brew install tmux`

Put config file `alacritty.yml` into alacritty config location - `~/.config/alacritty/`

Put `themes` folder with color themes from https://github.com/eendroroy/alacritty-theme into  `~/.config/alacritty/`.

Put `tmux.conf` to `~/.tmux.conf`

### Configured keys

| Key                                               | Action                                               |
| ------------------------------------------------- | ---------------------------------------------------- |
| ![keys-font](keys.assets/keys-font.png)           | ResetFontSize, IncreaseFontSize, DecreaseFontSize    |
| ![new-window](keys.assets/new-window.png)         | Create a new window (Tab)                            |
| ![nav-window](keys.assets/nav-window.png)         | Select the next/previous window                      |
| ![select-window](keys.assets/select-window.png)   | Select window 0-9 (window 0 is mapped to key 1)      |
| ![split-window](keys.assets/split-window.png)     | Split window (create pane) horizontally (left/right) |
| ![split-window-v](keys.assets/split-window-v.png) | Split window (create pane) vertically (top/bot       |
| ![nav-pane](keys.assets/nav-pane.png)             | Go to the next pane left/right/top/bottom            |
| ![move-pane](keys.assets/move-pane.png)           | Move current pane to the next position               |
| ![resize-pane](keys.assets/resize-pane.png)       | Resize current pane by 1 row/column                  |
| ![break-pane](keys.assets/break-pane.png)         | Move current pane into a new window (‘break pane’)   |
| ![zoom-pane](keys.assets/zoom-pane.png)           | Zoom/unzoom current pane                             |