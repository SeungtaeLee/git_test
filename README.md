# git_test
test repo for practice using git

## Process of git command
- [x] init
- [x] add
- [x] commit
- [ ] push


## Push without username/password
- generate your own key
- register your public key on github
- add your private key to ssh-agent
```bash
>eval "$(ssh-agent -s)"
>ssh-add "your private key path"
>git remote set-url git@github.com:[username]/[project_name].git
```

