# alx-system_engineering-devops
Interesting DevOps for Backend project


### After creating an alias do the following to source it.
```bash
    source ./0-alias
    ls      # Run the sourced alias
```

### Setting up SSH in WSL
```bash
    ssh-keygen -t ed25519 -C "chidieonuoha@gmail.com"
    eval "$(ssh-agent -s)"
    ssh-add ~/.ssh/id_ed25519
    cat ~/.ssh/id_ed25519.pub

    git remote set-url origin git@github.com:chidie/alx-system_engineering-devops.git
    git push
```

>NOTE: Do a dos2unix <file> when you see such messages as -bash: ./102-odd: cannot execute: required file not found