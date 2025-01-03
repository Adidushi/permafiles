# Permafiles
This repository holds files which I want to update, but still need permalinks to the latest version (like a CV).  
To get a file's permalink, use `https://raw.githubusercontent.com/Adidushi/permafiles/main/<filename>`, where `<filename>` is a url-encoded version of the filename, you can get it with this:
```shell
python -c "import urllib.parse; print(urllib.parse.quote('<filename>'))"
```
