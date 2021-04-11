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

case insensitivity: 

```
find . -iname "test*"
```

#### 2. Find by file type


#### 3. Find by size


#### 4. Find by user


## Permissions

```
rwx

r - read
w - write
x - execute


u - user
g - group
o - other


chmod - for changing permission
``` 

