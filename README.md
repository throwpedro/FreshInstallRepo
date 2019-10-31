# FreshInstallRepo

# zsh for oh-my-zsh
Install and set up zsh as default
If necessary, follow these steps to install Zsh:

There are two main ways to install Zsh
with the package manager of your choice, e.g. sudo apt-get install zsh.

from source, following instructions from the Zsh FAQ

Verify installation by running zsh --version. Expected result: zsh 5.1.1 or more recent.

Make it your default shell: chsh -s $(which zsh)

Note that this will not work if Zsh is not in your authorized shells list (/etc/shells) or if you don't have permission to use chsh. If that's the case you'll need to use a different procedure.

Log out and login back again to use your new default shell.

Test that it worked with echo $SHELL. Expected result: /bin/zsh or similar.

Test with '$SHELL --version'. Expected result: 'zsh 5.1.1' or similar

# Oh-My-Zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

# Tmux
sudo apt-get install tmux

# vscode
https://code.visualstudio.com/docs/setup/linux
## vscode extensions
 - colonize
 - prettier/eslint (javascript)
 - phpcs
 - trailing spaces
 - import cost (javascript)


# npm
install node, npm, nvm

# keys
setup ssh and gdp keys
