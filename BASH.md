
# Bash

## Operations on files
### Merge all text files in a directory into one
```bash
$ cat * > merged-file
```

### Easy file sharing from the command line
```
zip -r directory.zip ./directory \
curl --upload-file ./directory.zip https://transfer.sh/directory.zip
```
