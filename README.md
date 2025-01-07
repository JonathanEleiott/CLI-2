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
  - git remote -> another location
    - add -> add connection
    - nickname -> name of connection (most commonly origin)
    - location -> where is the actual connection
  - git branch -> tells us which branch were on
    - -> -M [branch name] -> renames the main branch to the branch name specified
  - git push -> send your code somewhere
    - nickname -> nickname of the place that you want to send your code to
    - branch name -> which branch you want to push

- 3 stages
  - working directory (red)
  - staging area (green)
  - project

# File Naming and Structure for HTML and CSS files

- Don't use special characters (!, @, #, $, %, ^, &, *, (, ), /, +, =) (except hyphens)
- Don't use spaces (use hyphens)
- Start the file name with a letter
- Use all lowercase letters separated by hyphens
- Keep your file names short and descriptive
- ALWAYS put a file extension on files
