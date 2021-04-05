# linux-commands-notes

## find

(!) search for files in a directory hierarchy

```
find [-H] [-L] [-P] [-D debugopts] [-Olevel] [starting-point...]
       [expression]
```

#### 1. Find Files Using Name in Current Directory

```
find . -name test.txt
```

or using wildcard:

```
find . -name "test*"
```
