usage: git name-rev [<options>] <commit>...
   or: git name-rev [<options>]`--all`
   or: git name-rev [<options>]`--stdin`

   `--name-only`           print only names (no SHA-1)
   `--tags`                only use tags to name the commits
   `--refs` <pattern>      only use refs matching <pattern>
   `--exclude` <pattern>   ignore refs matching <pattern>

   `--all`                 list all commits reachable from all refs
   `--stdin`               read from stdin
   `--undefined`           allow to print `undefined` names (default)
   `--always`              show abbreviated commit object as fallback

