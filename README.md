My dotfiles.

Install
--------

Make sure there aren't any managed dotfiles already in $HOME - otherwise Fresh will crash during install.

    FRESH_LOCAL_SOURCE=designed27/dotfiles bash -c "`curl -sL get.freshshell.com`"
    
    # Or old mac --BAD--:
    GIT_SSL_NO_VERIFY=true FRESH_LOCAL_SOURCE=designed27/dotfiles bash -c "`curl -sLk get.freshshell.com`"

The included freshrc file will prompt for Git name and email to be saved locally. This prevents them from
being uploaded back with your own .dotfiles repository.
