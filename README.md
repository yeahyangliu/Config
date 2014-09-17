[user]
        name = YANG Liu
        email = yeah_yangliu@163.com
[branch]
        autosetupmerge = true
        autosetuprebase = always
[push]
        default = current
[alias]
        br = branch
        co = checkout
        cp = checkout -p
        ci = commit
        dc = diff --cached
        st=status
        pr = pull --rebase
        ps = push
        l = log --graph --pretty=format:'%C(red)%h%Creset %C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=short --all
[color]
        status = auto
        diff = auto
        branch = auto
        interactive = auto
