
[filter "lfs"]
        process = git-lfs filter-process
        required = true
        clean = git-lfs clean -- %f
        smudge = git-lfs smudge -- %f
[user]
        name = Rudeboyduke
        email = 148394670+Rudeboyduke@users.noreply.github.com