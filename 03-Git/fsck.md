usage: git fsck [<options>] [<object>...]

   `-v`,`--verbose`         be verbose
   `--unreachable`         show unreachable objects
   `--dangling`            show dangling objects
   `--tags`                report tags
   `--root`                report root nodes
   `--cache`               make index objects head nodes
   `--reflogs`             make reflogs head nodes (default)
   `--full`                also consider packs and alternate objects
   `--connectivity-only`   check only connectivity
   `--strict`              enable more strict checking
   `--lost-found`          write dangling objects in .git/lost-found
   `--progress`            show progress
   `--name-objects`        show verbose names for reachable objects

