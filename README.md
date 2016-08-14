#Android gcc

##Perl Android ndk gcc compiler

**This compiler allows  one to compile native code ie _C_ into Android binary**

#Usage
In order to use the tool replace the below variables with their respective values.

- $DROID = *"Your Android NDK Path"*
- $VERSION = *"Version of armebi to use eg 4.8"*
- $ABASE = *"$DROID/platforms/android-3"*
- $ALIB = *"$ABASE/arch-arm/usr/lib"*;
- $TOOLCHAIN = *"$DROID/toolchains/arm-linux-androideabi-$VERSION/prebuilt/linux-x86_64"*;
- $GCC = *"$TOOLCHAIN/bin/arm-linux-androideabi-gcc"*;

##How to use
- **Window**
> perl agcc.l input.c -o output

- **Linux**
> 1. chmod +x agcc.pl
> 2. ./agcc.l input.c -output

:+1: Yall enjoy
