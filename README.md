
# SQLite database engine

## Windows上mingw64编译

```bash
> mkdir build & cd build
> mingw64 (/d/devtools/msys64/mingw64.exe)
> export PATH=/D/devtools/Qt/Qt5.12.12/Tools/mingw730_64/bin:$PATH
> cd /D/workspace/sqlite.3.44.0/build
> ../configure --prefix=/d/devtools/sqlite.3.44.0 --disable-dependency-tracking
> mingw32-make.exe
> mingw32-make.exe install
```


D:/devtools/msys64/usr/bin/sh.exe ./libtool  --tag=CC   --mode=compile gcc -DPACKAGE_NAME=\"sqlite\" -DPACKAGE_TARNAME=\"sqlite\" -DPACKAGE_VERSION=\"3.44.0\" -DPACKAGE_STRING=\"sqlite\ 3.44.0\" -DPACKAGE_BUGREPORT=\"http://www.sqlite.org\" -DPACKAGE_URL=\"\" -DPACKAGE=\"sqlite\" -DVERSION=\"3.44.0\" -D_FILE_OFFSET_BITS=64 -DHAVE_STDIO_H=1 -DHAVE_STDLIB_H=1 -DHAVE_STRING_H=1 -DHAVE_INTTYPES_H=1 -DHAVE_STDINT_H=1 -DHAVE_STRINGS_H=1 -DHAVE_SYS_STAT_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_UNISTD_H=1 -DSTDC_HEADERS=1 -DLT_OBJDIR=\".libs/\" -DHAVE_USLEEP=1 -DHAVE_DECL_STRERROR_R=0 -DHAVE_ZLIB_H=1 -I. -I..    -D_REENTRANT=1 -DSQLITE_THREADSAFE=1 -DSQLITE_ENABLE_MATH_FUNCTIONS -DSQLITE_ENABLE_FTS4 -DSQLITE_ENABLE_FTS5 -DSQLITE_ENABLE_RTREE -DSQLITE_ENABLE_GEOPOLY -DSQLITE_HAVE_ZLIB  -g -O2 -c -o sqlite3.lo ../sqlite3.c
libtool: compile:  gcc "-DPACKAGE_NAME=\\sqlite\" -DPACKAGE_TARNAME=\"sqlite\" -DPACKAGE_VERSION=\"3.44.0\" -DPACKAGE_STRING=\\sqlite 3.44.0\"" "-DPACKAGE_BUGREPORT=\\http://www.sqlite.org\" -DPACKAGE_URL=\"\" -DPACKAGE=\"sqlite\" -DVERSION=\"3.44.0\" -D_FILE_OFFSET_BITS=64 -DHAVE_STDIO_H=1 -DHAVE_STDLIB_H=1 -DHAVE_STRING_H=1 -DHAVE_INTTYPES_H=1 -DHAVE_STDINT_H=1 -DHAVE_STRINGS_H=1 -DHAVE_SYS_STAT_H=1 -DHAVE_SYS_TYPES_H=1 -DHAVE_UNISTD_H=1 -DSTDC_HEADERS=1 -DLT_OBJDIR=\".libs/\" -DHAVE_USLEEP=1 -DHAVE_DECL_STRERROR_R=0 -DHAVE_ZLIB_H=1 -I. -I.. -D_REENTRANT=1 -DSQLITE_THREADSAFE=1 -DSQLITE_ENABLE_MATH_FUNCTIONS -DSQLITE_ENABLE_FTS4 -DSQLITE_ENABLE_FTS5 -DSQLITE_ENABLE_RTREE -DSQLITE_ENABLE_GEOPOLY -DSQLITE_HAVE_ZLIB -g -O2 -c -o sqlite3.lo ../sqlite3.c"  -DDLL_EXPORT -DPIC -o .libs/sqlite3.o
gcc.exe: fatal error: no input files

