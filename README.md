# zsh-customization

### Case-insensitive autocompletion

Add following lines to ```~/.zshrc```:
```
autoload -Uz compinit && compinit
zstyle ':completion:*' matcher-list 'm:{a-zA-Z}={A-Za-z}'
```
