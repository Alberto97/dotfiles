1. Clone the repository
2. Source configuration by appending these lines to .zshrc

```bash
# Add user customizations
if [[ -e .zshrc.local ]]; then
  source .zshrc.local
fi
```
3. Copy dotfiles

```bash
cp -R dotfiles/bin $HOME/.local
```