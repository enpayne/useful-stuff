# useful-stuff

### delete all local branches which have already been merged into develop
`!sh -c 'git branch --merged develop | grep -v develop | xargs -n 1 git branch -d'`