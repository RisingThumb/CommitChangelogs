# CommitChangelogs
Automatically generate your CHANGELOG.md and commits it

# What it does?
This simple script generates your CHANGELOG.md for all commits made. It's intended to replace normal `git commit` commands that don't add tags or update changelogs with one that does.

# Installation
## Linux
- Get the script `wget https://raw.githubusercontent.com/Malod219/CommitChangelogs/master/git-commit`
- Give it execution permissions `chmod +x git-commit`
- Run it without parameters to get usage info `./git-commit`

## Windows and Mac
- Go to this site `https://raw.githubusercontent.com/Malod219/CommitChangelogs/master/git-commit`
- Right click, Save page as `git-commit` in your local git repository
- Give it execution permissions in a shell `chmod +x git-commit`(Windows user I recommend Git Bash)
- Run it without parameters to get usage info `./git-commit`

# Usage
```
Usage: ./git-commit -m message -t version tag
        -m Commit message
        -b Version tag
```
## Example usage:
- `./git-commit` to get help commands
- `./git-commit -m "Pizza Time"` to generate a changelog, and commit with "Pizza Time" as the commit message
- `./git-commit -m "Pizza Time" -t "v1.0"` to generate a changelog, commit with Pizza Time and give the commit a tag

# Contribution
This script is by no means complete. I wrote it as a script to generate changelogs for git projects using my git commit log
