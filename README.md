This is forked and modified from https://github.com/tux-mind/libbthread by tux-mind

I did some minor changes to this library for use within an Android project in Android studio (which mostly affects the exact content declarations in the
CMakeList.txt file) and added pt-internal.h from the Android Open Source project for use in Android Studio projects.

For reference, tux-mind states about the libbthread library itself:

libbthread
==========

library that provide some missing posix threading function to the bionic libc.

Tux-mind found that the bionic libc does not provide some POSIX thread functions like `pthread_cancel`, `pthread_testcancel` and so on.

so, tux-mind developed this library, which according to tux-mind exploits some unused bits in the bionic thread structure.

there is many thing to develop, like support for deferred cancels, but basic thread cancellation works :smiley:

tux-mind hopes that you find this library useful :wink: 

-- tux_mind

License
==========

Project is licensed under GNU LGPL v2.0 (Library General Public License)

pt-internal.h - is from The Android Open Source Project and licensed under Apache License, Version 2.0



