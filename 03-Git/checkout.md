usage: git checkout [<options>] <branch>
   or: git checkout [<options>] [<branch>]`--` <file>...

   `-q`,`--quiet`           suppress progress reporting
   `-b` <branch>           create and checkout a new branch
   `-B` <branch>           create/reset and checkout a branch
   `-l`                    create reflog for new branch
   `--detach`              detach HEAD at named commit
   `-t`,`--track`           set upstream info for new branch
   `--orphan` <new-branch>
                          new unparented branch
   `-2`,`--ours`            checkout our version for unmerged files
   `-3`,`--theirs`          checkout their version for unmerged files
   `-f`,`--force`           force checkout (throw away local modifications)
   `-m`,`--merge`           perform a 3-way merge with the new branch
   `--overwrite-ignore`    update ignored files (default)
   `--conflict` <style>    conflict style (merge or diff3)
   `-p`,`--patch`           select hunks interactively
   `--ignore-skip-worktree-bits`
                          do not limit pathspecs to sparse entries only
   `--ignore-other-worktrees`
                          do not check if another worktree is holding the given ref
   `--recurse-submodules`[=<checkout>]
                          control recursive updating of submodules
   `--progress`            force progress reporting

