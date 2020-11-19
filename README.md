# setpaths-cli
A CLI command to set up a folder structure for development.

This will create a development folder structure in ${your_home_directory}/Documents/dev

## How to
```
 1. npm i -g @hakansundstrom/setpaths-cli
 2. run 'setpaths createfolders' from your terminal.
 3. Copy the generated aliases into your .zshrc or .bashrc file via a texteditor via 'nano ~/.zshrc' or 'vim ~/.zshrc'
 4. Save to file. (Read about 'nano' or 'vim' editor if you dont know how to write to file.) nano is the most beginner friendly.
 4. Done! Write something like 'p.dev' or 'p.sandbox' or 'p.node' to terminal, all paths have these shortcuts now.
```

All paths are accesible from terminal via 'p.{folderName}'.
The terminal will also display what folders and files are in there.

You can also fork this from github to a custom folder.

Execute this by entering 'node ${path-to-this-folder}/setpaths'. 

Customise your folder structure and paths in the fullPaths object as you'd like.

## The generated folder structure tree will look like this
````
dev
  bin # Executables
  production # Live projects
  debugging
  showcase # Showcase your skills repos
  work # Your work related repos
  sandbox # Just for learning and playing around
    git
    docker
    desktop # Desktop apps development
    mobile # Mobile apps development
    web
      frontend
      backend
      fullstack
    rdm # (Random)
      github # Random specific github repos
    langs
      c
      c++
      c#
      java
      python
        python3
      node
````

## Requirements:
Node
MacOS or Linux
