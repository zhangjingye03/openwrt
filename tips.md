# Some small tips when using git

## Merge with openwrt upstream

* `git merge <branch>` takes new commits from `<branch>`, **adds** them to the current branch, and automatically adds a "Merge" commit on top.

* `git rebase <branch>` takes new commits from `<branch>`, and **inserts** them under current changes.

## Submodule update

* `git submodule update --remote --init --recursive`, where `--remote` keeps submodule up-to-date with upstream.


