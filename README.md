
# SQLite Binaries

## Deprecation Notice

This repo is no longer updated. Built releases are now provided through TotalPave's SQLite [Releases](https://github.com/totalpaveinc/sqlite/releases).

The following binaries are produced by SQLite sources available in the [Public Domain](https://www.sqlite.org/copyright.html)

The built binaries found in this repository are licensed under MIT.

These binaries are built from the sources available Totalpave's [SQLite](https://github.com/totalpaveinc/sqlite) repository, which includes the original SQLite sources, with additional JNI wrappers provided by Total Pave Inc.

Refer to the sources [README](https://github.com/totalpaveinc/sqlite/blob/master/README.md) for more information.

## Runtime dependencies

For android, any application that uses this AAR file needs to include libc++_shared.so.

If your application doesn't already include this shared library, [android-libcxx](https://github.com/totalpaveinc/android-libcxx)
AAR Library can be imported, which will allow all linked native libraries to use a single source of libc++.
