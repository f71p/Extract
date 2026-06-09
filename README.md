# Extract
I hate having to remember syntax for different compression methods. 7zip, rar, zip, tar.zip ... whatever, this script handles it by just calling extract &lt;filename>

# Usage 
```
extract archive.tar.zst          # extract in place
extract -d loot.zip              # extract into its own dir (tarbomb-safe)
extract -l backup.tar.gz         # list contents, don't extract
extract -r *.gz                  # extract then delete sources
extract -o /tmp/out weird.bin    # extract into a specific dir
```

# Installation
```
sudo install -m 755 extract /usr/local/bin/extract   # or: cp to ~/.local/bin
```

