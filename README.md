# A set of configuration files for a MacBook

A collection of setup scripts for configuring a macbook

NB: Please take your time to review the scripts before using it. I take no responsiblity for whatever happens to your laptop after using it.

Credit:
I took inspiration from a lot of places i can hardly remember now but these are some of them:
 - https://www.freecodecamp.org/news/jazz-up-your-zsh-terminal-in-seven-steps-a-visual-guide-e81a8fd59a38/ for the major customizations.
 - https://medium.com/@ivanaugustobd/your-terminal-can-be-much-much-more-productive-5256424658e8

## Usage
Execute the bash script: `./configure-macbook.sh`

### Install Fonts and Colours
- See https://github.com/tonsky/FiraCode
- See https://github.com/mbadolato/iTerm2-Color-Schemes
- https://github.com/ryanoasis/nerd-fonts/releases/download/v2.0.0/Hack.zip

#### Remember to update Iterm2 preferences:
#### -> Profiles -> Text -> Font -> (Dejavu Sans Mono for Powerline or FiraCode Regular or Hack Nerd Font)
####                             -> font size -> 15
####             -> Colors -> Color Presets -> (Solarized Dark or Calamity)

### Reload Tmux conf
tmux source ~/.tmux.conf

### Install vundle plugins
- :PluginInstall
- vim +PluginInstall +qall

### To see available ~/.vimrc colorscheme
- ls -l /usr/share/vim/vim*/colors/
- Test with :colorscheme <colour_name>
