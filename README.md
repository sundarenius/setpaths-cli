# setpaths-cli
A CLI command to set up a folder structure for development.

This will create a development folder structure in ${your_home_directory}/Documents/dev

## How to
```
 1. sudo npm i -g @hakansundstrom/setpaths-cli
 2. run 'setpaths createfolders' from your terminal, this will create a .zshrc_aliases in your home folder.
 3. Add following line to your ${homedir}/.zshrc file: source ~/.zshrc_aliases
 4. Done! Open a new shell and write something like 'p.dev' or 'p.sandbox' or 'p.node' to terminal, all paths have these shortcuts now.
```

All paths are accesible from terminal via 'p.{folderName}'.
The terminal will also display what folders and files are in there.

You can also fork this from github to a custom folder.

Execute this by entering 'node ${path-to-this-folder}/setpaths'. 

Customise your folder structure and paths in the fullPaths object as you'd like.

## Maintainers
This project was built by Håkan Sundström and is maintained by him.
https://github.com/Sundarenius

## The generated folder structure tree will look like this
````
 Folder structure:
 dev
   bin # Executables
   production # Live projects
   debugging
   showcase # Showcase your skills repos
   work # Your work related repos
   oss # Open-source software contributions
   docs # Random dev. specific documents
   sandbox # Just for learning and playing around
     git
     docker
     desktop
     mobile
     web
       frontend
       backend
       fullstack
     rdm # (Random)
       github # Random specific github repos
     langs # Practice/play with different programming languages
       c
       c++
       c#
       java
       python
         python3
       node
       objective-c
       swift
       assembly
       javascript
       typescript
       php
       kotlin
       scala
````

## Requirements:
Node
MacOS or Linux
