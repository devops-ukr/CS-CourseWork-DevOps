usage: git send-pack [--all |`--mirror`] [--dry-run] [--force] [--receive-pack=<git-receive-pack>] [--verbose] [--thin] [--atomic] [<host>:]<directory> [<ref>...]
 `--all` and explicit <ref> specification are mutually exclusive.

   `-v`,`--verbose`         be more verbose
   `-q`,`--quiet`           be more quiet
   `--receive-pack` <receive-pack>
                          receive pack program
   `--exec` <receive-pack>
                          receive pack program
   `--remote` <remote>     remote name
   `--all`                 push all refs
   `-n`,`--dry-run`         dry run
   `--mirror`              mirror all refs
   `-f`,`--force`           force updates
   `--signed`[=<yes|no|if-asked>]
                          GPG sign the push
   `--push-option` <server-specific>
                          option to transmit
   `--progress`            force progress reporting
   `--thin`                use thin pack
   `--atomic`              request atomic transaction on remote side
   `--stateless-rpc`       use stateless RPC protocol
   `--stdin`               read refs from stdin
   `--helper-status`       print status from remote helper
   `--force-with-lease`[=<refname>:<expect>]
                          require old value of ref to be at this value

