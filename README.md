# Tyoras A(git)noster Theme for Oh My Zsh
Tyoras Agitnoster theme customizes your zsh prompt to show detailed information about the current git repository status.
I have added some personal customization from this theme.

It is based on both [agitnoster theme](https://gihtub.com/dbestevez/agitnoster-theme) and [agnoster theme](https://github.com/agnoster/agnoster-zsh-theme) included in [Oh My Zsh](https://github.com/robbyrussell/oh-my-zsh) and [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt).

![Theme preview](preview.png)

## Install
Run the following commands to install tyoras agitnoster theme:
```
git clone https://github.com/tyoras/tyoras-agitnoster-theme.git
cd tyoras-agitnoster-theme
./install.sh
```


## Compatibility
Tyoras Agitnoster theme requires an unicode-compatible font to show git status properly.

To check if your terminal and font support all required characters run the following command:

```
echo "⮀ ± ⭠ ➦ ✔ ✘ ⚡"
```

The result should look like this:

![Compatibility preview](comp-preview.png)

It is recommended to check the [Powerline fonts](https://github.com/powerline/fonts) project. It includes some patched fonts that are fully compatible with agitnoster theme.
