# Fran's `zsh` prompt
The `zsh` prompt that I've been using for the past several years. It expands and contracts based on whether you're `ssh`'d into another system, `su`'d to another user, in a `git` repo, &c.

It looks like this:

![image](https://github.com/franrogers/zsh-prompt-fran/assets/457615/edd54a85-d9a2-45e9-be69-8a251d1ad6cb)

Colors are based on your `ZLS_COLORS`, for consistency with syntax highlighting of directories and the like.

## Installing
Put `prompt_fran_setup` in your `fpath`, then:
```zsh
autoload -U promptinit && promptinit
prompt fran
```
