
git Configuration
git config --global user.name "Tarik Pektas"
git config --global user-email tarikpektas@hotmail.com


Help
git --help
git <command> --help (bspl git add --help)

Create an empty repo
git init  

Show the working tree status
git status

add file contents to the index
git add readme.md
git add .

record changes to the repo
git commit -m "my first commit"

show changes between commit, working tree
git diff

show changes staged for the next commit
git diff --staged(--cached)
