usage: git revert [<options>] <commit-ish>...
   or: git revert <subcommand>

   `--quit`                end revert or cherry-pick sequence
   `--continue`            resume revert or cherry-pick sequence
   `--abort`               cancel revert or cherry-pick sequence
   `-n`,`--no-commit`       don't automatically commit
   `-e`,`--edit`            edit the commit message
   `-s`,`--signoff`         add Signed-off-by:
   `-m`,`--mainline` <parent-number>
                          select mainline parent
   `--rerere-autoupdate`   update the index with reused conflict resolution if possible
   `--strategy` <strategy>
                          merge strategy
   `-X`,`--strategy-option` <option>
                          option for merge strategy
   `-S`,`--gpg-sign`[=<key-id>]
                          GPG sign commit

