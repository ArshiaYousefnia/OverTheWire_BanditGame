```sh
cd inhere/
find -size 1033c
```
this yields ```./maybehere07/.file2```:

```sh
cd maybehere07/
file .file2
```
this confirms file is readable and has suitable size. It's not executable as well:
```sh
cat .file2
```