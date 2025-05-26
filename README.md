1. Move everything to `~/.config/ghostty/`.
2. Install zsh.
3. Install powerlevel10k in `~/.powerlevel10k`.
4. Set `command = ..` to the .zsh binary, e.g. `command = /usr/bin/zsh`.
5. Add .zshrc these lines:

```bash
# <<< ghostty
if [[ "$TERM_PROGRAM" == ghostty ]]; then
	# enables powerlevel10k
	source ~/.config/ghostty/startup.zsh 
fi
# >>> ghostty
```

Great, you are set!
