usage: git format-patch [<options>] [<since> | <revision-range>]

   `-n`,`--numbered`        use [PATCH n/m] even with a single patch
   `-N`,`--no-numbered`     use [PATCH] even with multiple patches
   `-s`,`--signoff`         add Signed-off-by:
   `--stdout`              print patches to standard out
   `--cover-letter`        generate a cover letter
   `--numbered-files`      use simple number sequence for output file names
   `--suffix` <sfx>        use <sfx> instead of '.patch'
   `--start-number` <n>    start numbering patches at <n> instead of 1
   `-v`,`--reroll-count` <n>
                          mark the series as Nth re-roll
   `--rfc`                 Use [RFC PATCH] instead of [PATCH]
   `--subject-prefix` <prefix>
                          Use [<prefix>] instead of [PATCH]
   `-o`,`--output-directory` <dir>
                          store resulting files in <dir>
   `-k`,`--keep-subject`    don't strip/add [PATCH]
   `--no-binary`           don't output binary diffs
   `--zero-commit`         output all-zero hash in From header
   `--ignore-if-in-upstream`
                          don't include a patch matching a commit upstream
   `-p`,`--no-stat`         show patch format instead of default (patch + stat)

Messaging
   `--add-header` <header>
                          add email header
   `--to` <email>          add To: header
   `--cc` <email>          add Cc: header
   `--from`[=<ident>]      set From address to <ident> (or committer ident if absent)
   `--in-reply-to` <message-id>
                          make first mail a reply to <message-id>
   `--attach`[=<boundary>]
                          attach the patch
   `--inline`[=<boundary>]
                          inline the patch
   `--thread`[=<style>]    enable message threading, styles: shallow, deep
   `--signature` <signature>
                          add a signature
   `--base` <base-commit>  add prerequisite tree info to the patch series
   `--signature-file` <file>
                          add a signature from a file
   `-q`,`--quiet`           don't print the patch filenames

