# Matryoshka

> Why. Is. There. Always. Another. File!!!

Recursively unzip the file on the command line.

```bash
while [ "`find . -type f -name '*.zip' | wc -l`" -gt 0 ]; do find -type f -name "*.zip" -exec unzip -- '{}' \; -exec rm -- '{}' \;; done
```

The flag is `DOCTF{G00D_3FF0RT_BUT_1$_1T_0V3R?}`.
