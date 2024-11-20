## Repo Init ##
```bash
repo init -u https://github.com/Realme-GT-Neo-3/kernel_manifest.git -b main
```
## Sync Source ##
```bash
repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)
```
