Zsh-tugboat
===========

Oh-My-Zsh plugin for autocompletion of [tugboat](https://github.com/pearkes/tugboat/) command

## Installation

      cd /into/your/downloads/folder
      git clone git@github.com:DimitriSteyaert/Zsh-tugboat.git
      cp -r Zsh-tugboat/tugboat ~/.oh-my-zsh/custom/plugins

Now edit your ~/.zshrc file and add **tugboat** to the line that has **plugins=()**.
For example; mine is the following

    plugins=(git cp history rake rsync brew bundler osx vagrant sublime rvm gem tugboat)

Now open a new terminal window and autocompletion for the tugboat command should work.

## Usage

Just start hitting your TAB button and the arguments for the tugboat command should appear.

### SSH
I added autocompletion of the droplets in your account for the command **tugboat ssh**. So hit

    tugboat ssh TAB

and you will get a list of your droplets to choose from.

### Help
For help about the parameters on certain arguments you can just use

    tugboat help TAB

to get a list of arguments where more information is available.
