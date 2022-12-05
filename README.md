# API-development
This is my first project of API developement.
# system configurations

System-wide configurations when you install git software in your machine.
Typically, on linux it lies under `/etc/gitconfig`.
On windows it could be `c:\\program-files\\` or something similar (you can check).

# global configurations

This is again System-wide configuration.
Typically, on linux it lies under `~/gitconfig`.
On windows, it could be `C:\Users\$USER` (you can check).

We will configure our user name and email using commands -

`$ git config --global user.name "your-user-name"`
`$ git config --global user.email "your-email"`


# local configurations

when you run `git init` command, a hidden directory with name `.git` should be 
created. This is the directory that contains all your git configurations 
particular to your project (locally).

If you want to remove git tracking from your project, you can delete this `.git`
folder completely.