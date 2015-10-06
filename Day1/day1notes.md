# Front End Engineering Day 1
## October 6, 2015

----

- Front End Engineering
    - Everything we do lives in the browser.
    - Download and install Google Chrome.
    - Download and install Atom - text editor.

----

- Mac Tips:
    - command-Tab cycles through the applications you have open on the desktop
    - command-W closes files
    - command-c copies
    - command-v pastes
    - command-z undo
    - command-s saves
    - More shortcuts at https://support.apple.com/en-us/HT201236

----

- Atom:
    - Atom->install shell commands
    - Click this, enter password
    - allows you to use atom in your terminal
    - in terminal, navigate to a folder and type `atom .` and it will open every file in that folder in atom
    - command - t opens fuzzy finder to find files within the project you have open

----

- Terminal:
    - ~ is your home directory
    - need to install stuff to get terminal ready
    - iterm 2 - download and install and we will use this instead of terminal
    - Oh My Zsh: https://github.com/robbyrussell/oh-my-zsh
        - install via curl
          - copy and paste
        `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`

        into your iterm and hit enter - this will download and install Oh My Zsh via curl
    - Terminal prompt shows where you are: -> ~ means home directory, -> Desktop means desktop.
    - Commands:
        - `ls`: lists the contents of the folder that you are in in your terminal
          - `ls -a`: shows all files, including hidden files (usually begin with a dot)
          - `ls -al`: shows all files, and formats them pretty and shows extra info about them
          - `ls <foldername>`: view contents of the folder without going into the folder
        - Command-K: clears the terminal screen
        - `pwd`: print working directory - tells you where you are located in your file system
        - `cd`: change directory - moves you to a different directory
          - `cd ..`: changes directory to the one directly above it
          - `cd`: with nothing after it takes you home
          - `cd`: and the path to the folder takes you to that folder: cd ~/Desktop/images takes you to the images folder on the desktop
        - `open <filename>`: will open the file with the appropriate program
        - `touch <filename>`: creates a file with that name
        - pressing the up arrow goes through your command history. pressing it once is the most recent command, pressing it again does the command before that, etc.
        - `cat <filename>`: prints out to the terminal the contents of the file
          - `cat <path/filename>`: view contents of file in another directory
        - `rm <filename>`: deletes the file
          - `rm -r <foldername>`: deletes the folder and all the files in it recursively
        - `mkdir <foldername>`: creates a folder with that name
        - `sudo`: run command with root privelidges
        - `echo "text" >> <filename>`: puts text into that file
        - `cp <filename1> <path>/<filename2>`: copies filename1 into a file named filename2 in the path
        - `mv <filename1> <path>/<filename2>`: moves filename1 into a file named filename2 in the path. filename1 no longer exists after this.
        - `jump`: jumps to a point on your computer

  - HTML
    - Hypertext Markup Language
    - Allows you to create structure for your webpage
    - opening HTML tag: `<html>`
    - closing HTML tag: `<\html>`
    - header tags: `<h1>` through `<h6>`
    - paragraph tag: `<p>`
    - blockquote tag: `<blockquote>`
    - ordered list: `<ol>`
    - unordered list: `<ul>`
    - `<div class="image">`
    - `<img src = "http://www.placecage.com/c/800/500" alt="nick cage" />`
      - this tag is self-closing; there is no closing tag. no logical content for the inside of the image tag

  - Resources
    - w3schools is not great
      - w3fools.com documents what is inaccurate on w3schools
    - Use MDN (Mozilla Developer Network) instead: https://developer.mozilla.org/en-US/

  - CSS
    - Cascading Style Sheets
    - Allows you to give style to your HTML content
    - `<p style="font-side:50px;background-color:red;">
        This is a paragraph.
       </p>`
    - Inefficient to create style for each paragraph in the paragraph tags like this. Instead you can create a `<style>` tag.
    - Browswer applies the style closest to the content. (cascading!!)
