Everything should live in `~/.config/ghostty/`.
Add to .zshrc these lines:

```bash
# <<< ghostty
if [[ "$TERM_PROGRAM" == ghostty ]]; then
	# enables powerlevel10k
	source ~/.config/ghostty/startup.zsh 
fi
# >>> ghostty
```

Great, you are set!