# Initial MAC OS setup

To install required packages with brew:
```shell
brew bundle
```

### Pyenv
To append pyenv config to `.zshrc` file:
```shell
echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.zshrc
```
To install different python version and set `pyenv global`:
```shell
source pyenv/install_python_versions.sh
```

### Oh My Zsh
To install:
```shell
source oh_my_zsh/install.sh
```
To set custom theme:
```shell
source oh_my_zsh/set_zsh_theme
```

### FZF
Should be done after Oh-My-Zsh section
Run:
```shell
source fzf/enable_keybindings.sh
```

