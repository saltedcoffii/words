# `words`
`words` is a standard file on UNIX and UNIX-like operating systems, and is simply a newline-delimited list of dictionary words. It is used, for instance, by spell-checking programs. The words file is usually stored in `/usr/share/dict/words` or `/usr/dict/words`.

### Installation
Download the tarball or zip file from the [releases](https://github.com/words/releases) page or just clone the repository `git clone git://github.com/saltedcoffii/words`.

Unpack the tarball (if needed), cd into `words/dict` , and symlink your preferred language to `words`. Example:
```shell
ln -sv american-english words
```

As root, copy the `dist` file to `/usr/share/dict` or `/usr/local/share/dict`. On extremely ancient systems *c. 1990*, it might be `/usr/dict`.

Your package manager likely offers a this file in a package called `words` or `wordlist`.

### License
This project is public domain. See the [LICENSE](https://raw.github.com/saltedcoffii/words/master/LICENSE) file for more information.
