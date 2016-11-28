## Hello World Git Lfs
This is a demo repository to explore Git Large File Storage aka [git-lfs](https://git-lfs.github.com/)

## How Create a Git Lfs Repository
Here is a minimalistic example:

```
$ git lfs track "*.bin"
$ ls > foo.txt
$ ls > bar.txt
$ ls > cat.bin
$ ls > dog.bin
$ git add .
$ git commit -m "add some files"
$ git lfs ls-files
```

NOTE. For further info please take a look at [git lfs ls-files not listing lsf files](https://github.com/git-lfs/git-lfs/issues/1714)
