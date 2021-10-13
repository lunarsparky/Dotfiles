#Aliases

This document contains aliases for command replacements or shortcuts

## Bat instead of Cat

`alias cat='bat'`

## Fzf with Bat + Code

`alias preview="fzf --preview 'bat --color \"always\" {}'"`
_add support for ctrl+o to open selected file in VS Code_
`export FZF_DEFAULT_OPTS="--bind='ctrl-o:execute(code {})+abort'"`
