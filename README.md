# boring.helix

Helix editor configuration.

## Configuration

### `config.toml`

*   **Theme**: `catppuccin_macchiato`
*   **Line numbers**: Relative line numbers are enabled.
*   **Auto pairs**: Disabled for more control.
*   **Whitespace**: Trailing whitespace is automatically trimmed.
*   **Clipboard**: Uses `pasteboard` to fix clipboard issues with tmux.
*   **Keybindings**: Minimal tweaks to make vim users feel like home.
    *   `V` is mapped to `extend_line` (line selection).
    *   `x` is mapped to `delete_selection`.
    *   `X` is mapped to `delete_char_backward`.

### `languages.toml`

*   **Kotlin**: Configures the Kotlin language server.
## Installation

You can find installation instructions from [here](https://github.com/boringconfigs/#installation).
