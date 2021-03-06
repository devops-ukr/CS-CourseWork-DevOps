usage: git describe [<options>] [<commit-ish>...]
   or: git describe [<options>]`--dirty`

   `--contains`            find the tag that comes after the commit
   `--debug`               debug search strategy on stderr
   `--all`                 use any ref
   `--tags`                use any tag, even unannotated
   `--long`                always use long format
   `--first-parent`        only follow first parent
   `--abbrev`[=<n>]        use <n> digits to display SHA-1s
   `--exact-match`         only output exact matches
   `--candidates` <n>      consider <n> most recent tags (default: 10)
   `--match` <pattern>     only consider tags matching <pattern>
   `--exclude` <pattern>   do not consider tags matching <pattern>
   `--always`              show abbreviated commit object as fallback
   `--dirty`[=<mark>]      append <mark> on dirty working tree (default: "-dirty")
   `--broken`[=<mark>]     append <mark> on broken working tree (default: "-broken")

