
# Bash

## Operations on files
### Merge all text files in a directory into one
```bash
$ cat * > merged-file
```

### Share file
```
zip -r directory.zip ./directory \
curl --upload-file ./directory.zip https://transfer.sh/directory.zip
```
