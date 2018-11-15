# git-multihooks
Installer and orchestration tool for multiple hooks in Git

## Install

```bash
$ curl https://raw.githubusercontent.com/halprin/git-multihooks/master/git-multihooks > /usr/local/bin/git-multihooks
$ chmod +x /usr/local/bin/git-multihooks
```

## Use

```bash
$ git multihooks add <git hook name e.g. pre-commit> <path to an executable script to use>
$ git multihooks remove <git hook name e.g. pre-commit> <script name to remove>
```
