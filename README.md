# Kryptic Ultimate

Current release: **1.8**

Keep these files in the same folder:

- `Kryptic Ult Loader.exe`
- `version.txt`
- `README.md`
- `icons` (combat, config, visuals, exploit, misc, logo)

The loader checks this folder against GitHub on startup. If `version.txt` on GitHub is newer, it downloads the new loader and README, deletes the old loader in this folder, then asks you to reopen as administrator. Missing tab icons are downloaded into `icons` automatically.
