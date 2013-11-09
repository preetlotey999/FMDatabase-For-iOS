FMDatabase
==========

This is an Objective-C wrapper around SQLite. Since FMDB is built on top of SQLite. If using FMDB with SQLCipher you must use the FMDB/SQLCipher subspec. The FMDB/SQLCipher subspec declares SQLCipher as a dependency, allowing FMDB to be compiled with the -DSQLITE_HAS_CODEC flag.
