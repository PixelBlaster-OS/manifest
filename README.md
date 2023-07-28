<p align="center">
  <img src="PixelBlaster.png" />
</p>  

Credits:
=======
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
 * [**StatixOS**](https://github.com/StatixOS)

-----------------------------------------------------------------------------

### Getting Started: ###

To initialize your local repository, use a command like this:

```bash

repo init -u https://github.com/PixelBlaster-OS/manifest -b 13

# Sync
repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Building ###

The included build script `./build.sh` handles all the building steps for the specified device
automatically.

Run the following command to find out how to use the script.
```bash
$ ./build.sh -h
```

### Submitting Patches ###

Patches are always welcome! Fork any of the repos and make pull requests. Maintain Proper Authorship if picking someone else's commits.

### Apply for Official Maintainership ###

You can apply for officialy maintaining the ROM for your device by filling the form below.

https://forms.gle/7GJucJaVJmWeszfV9

After filling the form, contact @TheTablaster on telegram for further details.