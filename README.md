# setpaths-cli
A CLI command to set folder structures for development.

This will create a development folder structure in ${your_home_directory}/Documents/dev

## How to
```
 1. npm i -g @hakansundstrom/setpaths-cli
 2. run 'setpaths createfolders' from you terminal.
 3. Copy the generated aliases into your .zshrc or .bashrc file via a texteditor via 'nano ~/.zshrc' or 'vim ~/.zshrc'
 4. Save to file. (Read about 'nano' or 'vim' editor if you dont know how write to file.) nano is the most beginner friendly.
 4. Done! Try putting in something like 'p.dev' or 'p.sandbox' or 'p.node' to terminal, all paths have these shortcuts now.
```

You can also fork this from github to a custom folder.

Execute this by entering 'node ${path-to-this-folder}/setpaths'. 

Customise your folder structure and paths in the fullPaths object as you'd like.

## Requirements:
Node
MacOS or Linux
