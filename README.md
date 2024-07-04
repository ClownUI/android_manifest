
![banner](https://raw.githubusercontent.com/ClownUI/android_manifest/vic/clown.png)
# ClownUI

## Getting Started ## 
---------------
To get started with the ClownUI sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
repo init -u https://github.com/ClownUI/android_manifest.git -b vic --git-lfs
```

## Then sync up: ##

```bash
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
```

### Build our source ###

```bash
. build/envsetup.sh
lunch clown_$devicecodename-userdebug
make clown -j$(nproc --all) | tee log.txt
```
