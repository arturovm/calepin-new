# [Calepin](http://calepin.co) new file creator

### Installation

    git clone https://github.com/cormacrelf/calepin-new
    cd calepin-new
    
    # assuming ~/bin/ exists and is in your $PATH
    ln -s ./calepin ~/bin/calepin

### Usage

To create a file named "file-name" in your ~/Dropbox/Apps/Calepin/ folder:

    % calepin file-name


### Configuration

To change the text editor used by the `calepin` command, add the following line to your `~/.bash_profile` (or `~/.zshrc`, etc.):

    # To change to, for example, an application in 
    # /Applications called Byword (http://bywordapp.com):
    
    export CALEPIN_EDITOR="Byword"
    
    # Same goes for shell commands. These take priority 
    # (eg a command named `vim` will take priority over 
    # an Application called "vim"). EG:
    
    export CALEPIN_EDITOR="vim"

