# Kryptic Ultimate

Keep these three files in the same folder:

- `Kryptic Ult Loader.exe`
- `version.txt`
- `README.md`

The loader checks this folder against GitHub on startup. If `version.txt` on GitHub is newer, it downloads the new loader and README, deletes the old loader in this folder, then asks you to reopen as administrator.
