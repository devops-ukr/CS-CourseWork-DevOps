usage: git pack-objects`--stdout` [<options>...] [< <ref-list> | < <object-list>]
   or: git pack-objects [<options>...] <base-name> [< <ref-list> | < <object-list>]

   `-q`,`--quiet`           do not show progress meter
   `--progress`            show progress meter
   `--all-progress`        show progress meter during object writing phase
   `--all-progress-implied`
                          similar to`--all-progress` when progress meter is shown
   `--index-version` <version[,offset]>
                          write the pack index file in the specified idx format version
   `--max-pack-size` <n>   maximum size of each output pack file
   `--local`               ignore borrowed objects from alternate object store
   `--incremental`         ignore packed objects
   `--window` <n>          limit pack window by objects
   `--window-memory` <n>   limit pack window by memory in addition to object limit
   `--depth` <n>           maximum length of delta chain allowed in the resulting pack
   `--reuse-delta`         reuse existing deltas
   `--reuse-object`        reuse existing objects
   `--delta-base-offset`   use OFS_DELTA objects
   `--threads` <n>         use threads when searching for best delta matches
   `--non-empty`           do not create an empty pack output
   `--revs`                read revision arguments from standard input
   `--unpacked`            limit the objects to those that are not yet packed
   `--all`                 include objects reachable from any reference
   `--reflog`              include objects referred by reflog entries
   `--indexed-objects`     include objects referred to by the index
   `--stdout`              output pack to stdout
   `--include-tag`         include tag objects that refer to objects to be packed
   `--keep-unreachable`    keep unreachable objects
   `--pack-loose-unreachable`
                          pack loose unreachable objects
   `--unpack-unreachable`[=<time>]
                          unpack unreachable objects newer than <time>
   `--thin`                create thin packs
   `--shallow`             create packs suitable for shallow fetches
   `--honor-pack-keep`     ignore packs that have companion .keep file
   `--compression` <n>     pack compression level
   `--keep-true-parents`   do not hide commits by grafts
   `--use-bitmap-index`    use a bitmap index if available to speed up counting objects
   `--write-bitmap-index`  write a bitmap index together with the pack index

