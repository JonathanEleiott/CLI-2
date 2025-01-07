# CLI (Command Line Interface) commands

- Tell your computer what to do
- Commands
  - ls -> lists out the contents of the current directory (folder)
  - cd [directory name] -> changes the directory
    - .. -> goes up one directory
    - / -> separates navigating multiple directories
  - mkdir [directory name] -> creates a new directory
  - touch [file name] -> creates a new file
  - mv and rm -> moving and removing a file (I recommend doing this in the explorer bar)
    - NEVER RUN THIS COMMAND -> rm -rf
  - code [directory name] -> open VS Code at the specified directory
    - . -> refers to the currect directory
  - && -> do one command after another finishes
- Flags
  - extensions of a command
  - Example: ls -a (shows all files and directories in the current folder)

# Git vs GitHub

- Git -> version control system using git commands that keep track of the history of files
- GitHub -> place to store your projects (repository)

- git commands
  - git init -> allows a project to use git commands
  - git status -> shows what has been added/changed/deleted since the last commit
  - git add [file names] -> moves the files/folders from the working directory area to the staging area
  - git commit -> takes everything from the staging area and makes it permanent
    - -m "message" -> shortcut for writing a message on your commit

- 3 stages
  - working directory (red)
  - staging area (green)
  - project