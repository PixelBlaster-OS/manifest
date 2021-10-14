<p align="center">
  <img src="PixelBlaster.png" />
</p>  

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**Potato Open Sauce Project**](https://github.com/PotatoProject)
 * [**LineageOS**](https://github.com/LineageOS)

-----------------------------------------------------------------------------

### Getting Started: ###

To initialize your local repository, use a command like this:

```bash

repo init -u https://github.com/PixelBlaster-OS/manifest -b 12

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash

# Set up environment
$ . build/envsetup.sh

# Choose a target
$ lunch aosp_$device-userdebug

# Build the code
$ mka bacon -jX
```

### Submitting Patches ###

Patches are always welcome! Fork any of the repos and make pull requests. Maintain Proper Authorship if picking someone else's commits.

### Apply for Official Maintainership ###

You can apply for officialy maintaining the ROM for your device by filling the form below.

https://forms.gle/7GJucJaVJmWeszfV9

After filling the form, contact @TheTablaster on telegram for further details.