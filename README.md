# [Calepin](http://calepin.co) new file creator

Removes most friction in the process of starting to write a new blog entry. Don't think, just write. 

### Installation

    git clone https://cormacrelf@github.com/cormacrelf/calepin-new.git
    cd calepin-new
    
    # assuming ~/bin/ exists and is in your $PATH
    # (otherwise, try /usr/bin/calepin)
    
    ln -s $(pwd)/calepin ~/bin/calepin

### Usage

To create a file named "file-name.md" in your ~/Dropbox/Apps/Calepin/ folder:

    calepin -f file-name
    
    # note that you don't need the ".md" extension

A few other useful optional arguments are available. You can set a title for the post and insert the current date, should you chose to do so.

For example:

    # available arguments are:
    # -t title
    # -d insert date (flag only)
    # -h show help message
    
    calepin -f post123.md -t "Hello World!" -d
    
    # This creates a file named 'post123.md', with the title
    # 'Hello World!' and inserts the current date, all according
    # to the calepin formatting guide.


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
##### Additions by [@ArturoVM](http://twitter.com/ArturoVM).
