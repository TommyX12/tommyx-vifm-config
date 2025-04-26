# tommyx-vifm-config

## Setup
- Install [Vifm](https://vifm.info/)
    - `brew install vifm` (macOS)
- Install optional dependencies
    - `fzf`
        - See https://github.com/TommyX12/tommyx-shell
    - `rg`
        - `brew install ripgrep` (macOS)
    - `poppler`
        - `brew install poppler` (macOS)
    - `fd`
        - `brew install fd` (macOS)
    - `pygmentize`
        - `brew install pygments` (macOS)
- Create symlink for config
    - `mkdir -p ~/.config/vifm`
    - `ln -s <path-to-repo>/vifmrc ~/.config/vifm/vifmrc`
