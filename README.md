# Programs

The dotfiles/ directory is located in `$HOME/git/dotfiles`.

## Ranger

Ranger is installed with:

[ueberzugg](https://github.com/jstkdng/ueberzugpp) for image preview.

`.md` files are previewed with [glow](https://github.com/charmbracelet/glow)

dev icons in preview with [dev-icons](https://github.com/alexanderjeurissen/ranger_devicons)

## Nvim

Nvim is installed with [kickstart](https://github.com/nvim-lua/kickstart.nvim)

### Plugins

   | Plugin                                                                              | Purpose                                  |
   | :-                                                                                  | :-                                       |
   | [Startup-Nvim](https://github.com/startup-nvim/startup.nvim)                        | Startup menu / greeter                   |
   | [Lualine](https://github.com/nvim-lualine/lualine.nvim)                             |                                          |
   | [Nvim-Tree](https://github.com/nvim-tree/nvim-tree.lua)                             | File explorer                            |
   | [Render-Markdown](https://github.com/MeanderingProgrammer/render-markdown.nvim)     | Render markdown files in editor          |
   | [Tabular](https://github.com/godlygeek/tabular)                                     | Table by delimiters                      |
   | [Comment](https://github.com/numToStr/Comment.nvim)                                 | Comment macro                            |
   | [Rainbow-Delimiters](https://github.com/HiPhish/rainbow-delimiters.nvim)            | Matching delimiters are colored the same |
   | [Auto-Pair](https://github.com/windwp/nvim-autopairs)                               | Automatically pair delimiters            |
   | [Tiny-Inline_diagnostic](https://github.com/rachartier/tiny-inline-diagnostic.nvim) | Prettier diagnostic messages             |
   | [Trouble](https://github.com/folke/trouble.nvim)                                    | Quickfix list navigation                 |
   | [Conform](https://github.com/stevearc/conform.nvim)                                 | Code formatting                          |
   | [Todo-Comments](https://github.com/folke/todo-comments.nvim)                        | Highlight TODO in comments               |
   | [Nvim-Ufo](https://github.com/kevinhwang91/nvim-ufo)                                | Fold manager                             |
   | [Neominimap](https://github.com/plugins.neominimap)                                 | Code Minimap                             |
   | [Nvim-Colorizer](https://github.com/NvChad/nvim-colorizer.lua)                      | Color Text Inline                        |

### Git

   | Plugin                                         | Purpose      |
   | :-                                             | :-           |
   | [Fugitive](https://github.comtpope/vim-fugitive)       |              |
   | [Rhubarb](https://github.com/tpope/vim-rhubarb)        |              |
   | [Diffview](https://github.com/sindrets/diffview.nvim)  | Merge Editor |
   | [Gitsigns](https://github.com/lewis6991/gitsigns.nvim) |              |

## Alacritty 

Alacritty is used as the default terminal emulator.
The color theme is [Blood Moon](https://github.com/dguo/blood-moon)

## Zshell

Zshell is installed with manually managed plugins:

- [fast-syntax-highlighting](https://github.com/zdharma-continuum/fast-syntax-highlighting)
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions)
- [zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete)

The Prompt is managed using [starship](starship.rc).

The [pipes.sh](https://github.com/pipeseroni/pipes.sh) is set as the inactivity terminal screen saver (default after 300 seconds).

## Fonts
The [Hack](https://github.com/source-foundry/Hack) typeface is installed and used as default monospaced font.



# Keybinds

## General

 | Action                    | Bind        |
 | :------------------------ | :---------- |
 | Open Terminal (Alacritty) | `SUPER+T`   |

## Zshell

 | Action                  | Mode        | Bind                 |
 | :------                 | :---------- | :-----------         |
 | Enter Normal Mode       | Insert      | `Esc`                |
 | Enter Insert Mode       | Normal      | `i`,`a`,`o`          |
 | Search Histroy Prefixed | Insert      | `CTRL+Q`, `CTRL+P`   |
 | Search Histtory Prefiex | Normal      | `SHIFT+J`, `SHIFT+K` |

## NVim

  | Action                  | Mode        | Bind        |
  | :---------------------- | :---------- | :---------- |
  | Toggle Relative-Numbers | Normal      | ``CTRL+` `` |
  | Open Minimap Menu       | Normal      | `SPACE>+M`  |
  | Open Debug Menu         | Normal      | `SPACE+Q`   |
  | Open Keybind Menu       | Normal      | `SPACE`     |
  | Open Fold Menu          | Normal      | `Z`         |

    
# Packages:

- [bat](https://github.com/sharkdp/bat)
- [rainbowcsv](https://pypi.org/project/rainbowcsv/)
- [fzf](https://github.com/junegunn/fzf)
- [zoxide](https://github.com/ajeetdsouza/zoxide)
-
-
-
-
-

# Todo:

- Configure and customise Nvim
- Title screen for nvim
- VimTeX
- Move distros to Fedora
- Set up Wayland, Nvidia drivers on Fedora
- Look into hyprland
- Set up wine for stuff like paint.net
- Set up recording with OBS or ffmpeg 
- Neofetch
- Ranger preview syntax highlighting
- Zshell "which-key" menu just like neovim's which-key plugin
-  Look into Tmux
