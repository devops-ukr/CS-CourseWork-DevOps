usage: git for-each-ref [<options>] [<pattern>]
   or: git for-each-ref [--points-at <object>]
   or: git for-each-ref [(--merged |`--no-merged`) [<commit>]]
   or: git for-each-ref [--contains [<commit>]] [--no-contains [<commit>]]

   `-s`,`--shell`           quote placeholders suitably for shells
   `-p`,`--perl`            quote placeholders suitably for perl
   `--python`              quote placeholders suitably for python
   `--tcl`                 quote placeholders suitably for Tcl

   `--count` <n>           show only <n> matched refs
   `--format` <format>     format to use for the output
   `--color`[=<when>]      respect format colors
   `--sort` <key>          field name to sort on
   `--points-at` <object>  print only refs which points at the given object
   `--merged` <commit>     print only refs that are merged
   `--no-merged` <commit>  print only refs that are not merged
   `--contains` <commit>   print only refs which contain the commit
   `--no-contains` <commit>
                          print only refs which don't contain the commit
   `--ignore-case`         sorting and filtering are case insensitive

