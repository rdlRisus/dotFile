## For zsh
```
git clone --recursive https://github.com/andresgongora/synth-shell.git](https://github.com/ohmyzsh/ohmyzsh)https://github.com/ohmyzsh/ohmyzsh
```

## For powerlevel10k
```
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
```

## zsh autosuggestions
```
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

## zsh syntax highlighting
```
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

## add this in your .zshrc
```
ZSH_THEME="powerlevel10k/powerlevel10k"
ENABLE_CORRECTION="true"
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```

## fixing permission errors in zsh
```
ZSH_DISABLE_COMPFIX=true
```
