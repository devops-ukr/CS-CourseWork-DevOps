usage: git rebase [-i] [options] [--exec <cmd>] [--onto <newbase>] [<upstream>] [<branch>]
   or: git rebase [-i] [options] [--exec <cmd>] [--onto <newbase>]`--root` [<branch>]
   or: git-rebase`--continue` |`--abort` |`--skip` |`--edit-todo`

Available options are
   `-v`,`--verbose`         display a diffstat of what changed upstream
   `-q`,`--quiet`           be quiet. implies`--no-stat`
   `--autostash`           automatically stash/stash pop before and after
   `--fork-point`          use 'merge-base`--fork-point`' to refine upstream
   `--onto` ...            rebase onto given branch instead of upstream
   `-p`,`--preserve-merges`
                          try to recreate merges instead of ignoring them
   `-s`,`--strategy` ...    use the given merge strategy
   `--no-ff`               cherry-pick all commits, even if unchanged
   `-m`,`--merge`           use merging strategies to rebase
   `-i`,`--interactive`     let the user edit the list of commits to rebase
   `-x`,`--exec` ...        add exec lines after each commit of the editable list
   `-k`,`--keep-empty`	     preserve empty commits during rebase
   `-f`,`--force-rebase`    force rebase even if branch is up to date
   `-X`,`--strategy-option` ...
                          pass the argument through to the merge strategy
   `--stat`                display a diffstat of what changed upstream
   `-n`,`--no-stat`         do not show diffstat of what changed upstream
   `--verify`              allow pre-rebase hook to run
   `--rerere-autoupdate`   allow rerere to update index with resolved conflicts
   `--root`                rebase all reachable commits up to the root(s)
   `--autosquash`         move commits that begin with squash
                          move commits that begin with squash!/fixup! under`-i`
   `--committer-date-is-author-date`
                          passed to 'git am'
   `--ignore-date`         passed to 'git am'
   `--signoff`             passed to 'git am'
   `--whitespace` ...      passed to 'git apply'
   `--ignore-whitespace`   passed to 'git apply'
   `-C` ...                passed to 'git apply'
   `-S`,`--gpg-sign`[=...]  GPG-sign commits

Actions:
   `--continue`            continue
   `--abort`               abort and check out the original branch
   `--skip`                skip current patch and continue
   `--edit-todo`           edit the todo list during an interactive rebase
   `--quit`                abort but keep HEAD where it is

