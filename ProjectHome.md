Fast SHA1 algorithm with a small memory footprint. Written in C++ and very easy to use.

Example of use:
```
unsigned char hash[20];
char hexstring[41];
sha1::calc("Teststring",10,hash); // 10 is the length of the string
sha1::toHexString(hash, hexstring);
```

There are only two files in the sources that are needed to use the sha1 algorithm in your own code: sha1.h and sha1.cpp.
The other files are there as unittesting and benchmarking.