# libzdb-3.2.2

Original source from https://bitbucket.org/tildeslash/libzdb

This repo for purpose include libzdb to my system (my OS is Ubuntu 18.04)

# How to build

``` sudo ./configure --prefix=/usr/include && sudo make && sudo make install```

After build, all header libs of libzdb will be here: `/usr/include/zdb`

# Use

Include to C program

#include <zdb/zdb.h>

# Compile and run

``` gcc <file_name>.c -lzdb -lpthread ```

```./a.out```
