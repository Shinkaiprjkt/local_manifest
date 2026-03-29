Initialize after init repo roms

```
git clone https://github.com/Mnskkyy/local_manifest.git -b 16-QPR2 .repo/local_manifests/
```

And sync repo
```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
