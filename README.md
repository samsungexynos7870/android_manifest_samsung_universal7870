# OrangeFox Recovery Project

### How to build for all devices ###

```bash
# Create dirs
$ mkdir ofox ; cd ofox

# Init repo
$ repo init --depth=1 -u https://gitlab.com/OrangeFox/Manifest.git -b fox_9.0

# Clone my local repo
$ git clone https://github.com/samsungexynos7870/manifest/android_manifest_samsung_universal7870.git -b orangefox .repo/local_manifests

# Sync
$ repo sync --no-repo-verify -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune -j`nproc`

# Build
$ mv .repo/local_manifests/build_ofox.sh .
$ . build_ofox.sh a3y17lte a6lte j5y17lte j6lte j7velte j7xelte j7y17lte on7xelte
```

## Credits
2019 @Astrako

## Contact
Telegram support group: https://t.me/joinchat/D1Jk_VbieGBXOWZt2y8O7A
