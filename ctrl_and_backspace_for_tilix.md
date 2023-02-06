https://github.com/gnunn1/tilix/issues/1348
# ZSH solution

```shell
# .zshrc

bindkey "^[[1;5C" forward-word
bindkey "^[[1;5D" backward-word
bindkey "^H" backward-kill-word
bindkey "^[[3;5~" kill-word
```
