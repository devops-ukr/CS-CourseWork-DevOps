usage: git cat-file (-t [--allow-unknown-type] |`-s` [--allow-unknown-type] |`-e` |`-p` | <type> |`--textconv` |`--filters`) [--path=<path>] <object>
   or: git cat-file (--batch |`--batch-check`) [--follow-symlinks] [--textconv |`--filters`]

<type> can be one of: blob, tree, commit, tag
   `-t`                    show object type
   `-s`                    show object size
   `-e`                    exit with zero when there's no error
   `-p`                    pretty-print object's content
   `--textconv`            for blob objects, run textconv on object's content
   `--filters`             for blob objects, run filters on object's content
   `--path` <blob>         use a specific path for`--textconv`/--filters
   `--allow-unknown-type`  allow`-s` and`-t` to work with broken/corrupt objects
   `--buffer`              buffer`--batch` output
   `--batch`[=<format>]    show info and content of objects fed from the standard input
   `--batch-check`[=<format>]
                          show info about objects fed from the standard input
   `--follow-symlinks`     follow in-tree symlinks (used with`--batch` or`--batch-check`)
   `--batch-all-objects`   show all objects with`--batch` or`--batch-check`

