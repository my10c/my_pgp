Wrapper script for gpg

```
mypgp 0.7
Copyright 1993 - 2021 (c) Badassops LLC
License BSD, http://www.freebsd.org/copyright/freebsd-license.html

Written by Luc Suryo <luc@badassops.com>
Wrapper script for gpg

Usage : mypgp [-h] [ option ... ]
 Options:
   -h this help page.
   -D debug mode, dry-run mode.
   -d value, the file to be decrypted
   -e value, the file to be encrypted
   -E value, edit key, modify entries
   -i value, imported public key from given file
   -G, interactive generate key
   -l, list all imported public key or given email address
   -p save public key in the file luc@badassops.com.acs
   -r value, recipient, to be use with the -e option
   -s value, search the given user and import key
   -S value, sign the key of the given email or key-id
   -x value, export the public key of the given email or key-id
   -X value, delete the key of the given email or key-id
   -v Show version
   -V value, show given key detail

Notes: during decryption there migth be some error
that  could  be ignored, so always check the decrypted file
```

Note
```
before usage make sure to edit the script and adjust the _my_key variable.
comments welcome :)
```


Enjoy

momo
