# Danny's Oh My ZSH customizations.

See here for more information: https://github.com/robbyrussell/oh-my-zsh/wiki/Customization#overriding-and-adding-themes

## Installation

Clone this repo into `~/.zsh-customizations` then, in `.zshrc`...

```shell
ZSH_CUSTOM=$HOME/.zsh-customizations
```

## Structure

```text
$HOME
└── .zsh-customizations
    ├── my_lib_patches.zsh
    ├── plugins
    │   └── my_plugin
    │       └── my_plugin.plugin.zsh
    └── themes
        └── dannysmith.zsh-theme
```
