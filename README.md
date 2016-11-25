# The best terminal setup for Mac.

![best terminal screenshot](https://raw.githubusercontent.com/samdoidge/the-best-terminal-setup-mac/master/best-terminal.png)

1. We install zsh via [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) as it is a superior shell to bash. The git plugin by default and improved autocomplete is reason enough.

2. We download [iTerm2](https://www.iterm2.com) as it allows visual customisation which the standard Mac terminal does not.

3. There are many themes available, but we have chosen agnoster. This requires custom fonts for helpful visual icons, we get them via cloning https://github.com/powerline/fonts and then running ./install.sh.

4. A great zshrc file exists in: https://github.com/samdoidge/config. Copy this zshrc file and rename to ~/.zshrc. You will need to replace the DEFAULT_USER with your username.

5. We have cloned https://github.com/samdoidge/config, so it is just a case of going to iTerm2 preferences -> 'Load preferences from a custom folder or URL', and select our config folder. Renaming 'samdoidge' to your username within the com.googlecode.iterm2.plist may be needed before hand. Restart iTerm2 and you should now have the best terminal setup for Mac.


