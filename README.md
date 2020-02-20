# custom-default-browser

Launch a specific browser depending on which workspace is currently in use.

## Installation

1. Copy `bin/custom-default-browser` to a directory in `$PATH` (e.g., `$HOME/bin`)
2. Edit settings in the `custom-default-browser` script as needed
3. Copy `share/custom-default-browser.desktop` to an applications directory (e.g., `$HOME/.local/share/applications`)
4. Run `xdg-settings set default-web-browser custom-default-browser.desktop`
