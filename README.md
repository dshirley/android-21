# android-21

This repo contains the source for the java classes found in the Android Open Source Project (AOSP).
The Android SDK manager distributes source for many of the system classes; these are usually found
in `$ANDROID_HOME/sources/android-21` (for example). The issue with the sources distributed by Google
is that quite a bit is missing.  This repo attempts to add the missing pieces (at least the ones
that **I** need ;-)

The end goal is to be able to point Eclipse at this repo when debugging and be able to step through
all of the AOSP java code. Android Studio currently doesn't allow setting the source lookup path, but
maybe you can symbolically link `${ANDROID_HOME}/sources/android-21` to this repo. 

## Additional sources included in this repo:

* `AOSP_ROOT/platform/external/conscrypt/`

