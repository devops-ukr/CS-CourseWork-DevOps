usage: git notes [--ref <notes-ref>] [list [<object>]]
   or: git notes [--ref <notes-ref>] add [-f] [--allow-empty] [-m <msg> |`-F` <file> | (-c |`-C`) <object>] [<object>]
   or: git notes [--ref <notes-ref>] copy [-f] <from-object> <to-object>
   or: git notes [--ref <notes-ref>] append [--allow-empty] [-m <msg> |`-F` <file> | (-c |`-C`) <object>] [<object>]
   or: git notes [--ref <notes-ref>] edit [--allow-empty] [<object>]
   or: git notes [--ref <notes-ref>] show [<object>]
   or: git notes [--ref <notes-ref>] merge [-v |`-q`] [-s <strategy>] <notes-ref>
   or: git notes merge`--commit` [-v |`-q`]
   or: git notes merge`--abort` [-v |`-q`]
   or: git notes [--ref <notes-ref>] remove [<object>...]
   or: git notes [--ref <notes-ref>] prune [-n |`-v`]
   or: git notes [--ref <notes-ref>] get-ref

   `--ref` <notes-ref>     use notes from <notes-ref>

