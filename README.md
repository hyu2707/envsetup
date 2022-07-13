For myself, quick cmd


## mac setup
in `~/.bash_profile`
```
export PS1="\[\033[36m\]\u\[\033[m\]@\[\033[32m\]\h:\[\033[33;1m\]\w\[\033[m\]\$ "
export CLICOLOR=1
export LSCOLORS=ExFxBxDxCxegedabagacad
alias ls='ls -GFh'

eval "$(/opt/homebrew/bin/brew shellenv)"
export PATH="/opt/homebrew/opt/openjdk/bin:$PATH"
```
