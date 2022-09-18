# Paranoid Android #

```bash
repo init --depth=1 -u https://github.com/rd-stuffs/manifest -b topaz
```

```bash
repo sync -c --force-sync --optimized-fetch --no-tags --prune -j$(nproc --all)
```
