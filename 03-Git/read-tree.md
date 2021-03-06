usage: git read-tree [(-m [--trivial] [--aggressive] |`--reset` |`--prefix`=<prefix>) [-u [--exclude-per-directory=<gitignore>] |`-i`]] [--no-sparse-checkout] [--index-output=<file>] (--empty | <tree-ish1> [<tree-ish2> [<tree-ish3>]])

   `--index-output` <file>
                          write resulting index to <file>
   `--empty`               only empty the index
   `-v`,`--verbose`         be verbose

Merging
   `-m`                    perform a merge in addition to a read
   `--trivial`             3-way merge if no file level merging required
   `--aggressive`          3-way merge in presence of adds and removes
   `--reset`               same as`-m`, but discard unmerged entries
   `--prefix` <subdirectory>/
                          read the tree into the index under <subdirectory>/
   `-u`                    update working tree with merge result
   `--exclude-per-directory` <gitignore>
                          allow explicitly ignored files to be overwritten
   `-i`                    don't check the working tree after merging
   `-n`,`--dry-run`         don't update the index or the work tree
   `--no-sparse-checkout`  skip applying sparse checkout filter
   `--debug-unpack`        debug unpack-trees
   `--recurse-submodules`[=<checkout>]
                          control recursive updating of submodules

