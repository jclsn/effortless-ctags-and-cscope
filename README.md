# Guide

Just execute these two commands and you are good to go:
```bash
git clone https://github.com/jclsn/effortless-ctags-and-cscope ~/.git_template
git config --global init.templatedir '~/.git_template'
```

You may want to change the names of the produces tags and cscope.out files to your liking. Vim also needs to be set up for cscope.

A .gitignore file with the following content is suggested to use in all your repositories
```
tags
cscope*
```

