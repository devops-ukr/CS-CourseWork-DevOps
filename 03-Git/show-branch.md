usage: git show-branch [-a |`--all`] [-r |`--remotes`] [--topo-order |`--date-order`]
		[--current] [--color[=<when>] |`--no-color`] [--sparse]
		[--more=<n> |`--list` |`--independent` |`--merge-base`]
		[--no-name |`--sha1-name`] [--topics] [(<rev> | <glob>)...]
   or: git show-branch (-g |`--reflog`)[=<n>[,<base>]] [--list] [<ref>]

   `-a`,`--all`             show remote-tracking and local branches
   `-r`,`--remotes`         show remote-tracking branches
   `--color`[=<when>]      color '*!+-' corresponding to the branch
   `--more`[=<n>]          show <n> more commits after the common ancestor
   `--list`                synonym to more=-1
   `--no-name`             suppress naming strings
   `--current`             include the current branch
   `--sha1-name`           name commits with their object names
   `--merge-base`          show possible merge bases
   `--independent`         show refs unreachable from any other ref
   `--topo-order`          show commits in topological order
   `--topics`              show only commits not on the first branch
   `--sparse`              show merges reachable from only one tip
   `--date-order`          topologically sort, maintaining date order where possible
   `-g`,`--reflog`[=<n>[,<base>]]
                          show <n> most recent ref-log entries starting at base

