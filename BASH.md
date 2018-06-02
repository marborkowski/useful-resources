
# Bash

## Operations on files
### Merge all text files in a directory into one
```bash
$ cat * > merged-file
```

### Share file
```
sudo zip -r content.zip ./wp-content \
curl --upload-file ./content.zip https://transfer.sh/content.zip
```
