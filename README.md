# [Calepin](http://calepin.co) new file creator

### Installation

    git clone https://cormacrelf@github.com/cormacrelf/calepin-new.git
    cd calepin-new
    
    # assuming ~/bin/ exists and is in your $PATH
    # (otherwise, try /usr/bin/calepin)
    ln -s $(pwd)/calepin ~/bin/calepin

### Usage

To create a file named "file-name.md" in your ~/Dropbox/Apps/Calepin/ folder:

    % calepin file-name
    
    # note that you don't need the ".md" extension


### Configuration

To change the text editor used by the `calepin` command, add the following line to your `~/.bash_profile` (or `~/.zshrc`, etc.):

    # To change to, for example, an application in 
    # /Applications called Byword (http://bywordapp.com):
    
    export CALEPIN_EDITOR="Byword"
    
    # Same goes for shell commands. These take priority 
    # (eg a command named `vim` will take priority over 
    # an Application called "vim"). EG:
    
    export CALEPIN_EDITOR="vim"

To change the directory used as the Calepin folder (eg. your Dropbox root folder is somewhere other than ~/Dropbox):

    # again in ~/.bash_profile (etc.)
    export CALEPIN_DIR="/path/to/Dropbox"

##### This is a [@cormacrelf](http://twitter.com/cormacrelf) jam.
