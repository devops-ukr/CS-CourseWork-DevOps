usage: git archive [<options>] <tree-ish> [<path>...]
   or: git archive`--list`
   or: git archive`--remote` <repo> [--exec <cmd>] [<options>] <tree-ish> [<path>...]
   or: git archive`--remote` <repo> [--exec <cmd>]`--list`

   `--format` <fmt>        archive format
   `--prefix` <prefix>     prepend prefix to each pathname in the archive
   `-o`,`--output` <file>   write the archive to this file
   `--worktree-attributes`
                          read .gitattributes in working directory
   `-v`,`--verbose`         report archived files on stderr
   `-0`                    store only
   `-1`                    compress faster
   `-9`                    compress better

   `-l`,`--list`            list supported archive formats

   `--remote` <repo>       retrieve the archive from remote repository <repo>
   `--exec` <command>      path to the remote git-upload-archive command

