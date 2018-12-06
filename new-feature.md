# New Feature

added another thing to our feature


# Here are some useful git flow / git commands

Initialize git flow into the project:
- git flow init -d

Mixed:
- git push --all
- git add .

https://danielkummer.github.io/git-flow-cheatsheet/


Back up the code on github:
git push --set-upstream origin feature/useful-git-commands

Start a new feature:
- git flow feature start useful-git-commands

Committing the feature:
- git commit -am "added useful commands"

Finish a new feature
- git flow feature finish useful-git-commands

Release:
- git flow release start 1.0.1
- git add .
- git commit -a
- git flow release finish 1.0.1 (will merge into master and develop)
- git push origin --all --follow-tags


