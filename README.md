Pharo-EJDB 
======

[Pharo](https://www.pharo.org) bindings for https://github.com/Softmotions/ejdb

[![Unit Tests](https://github.com/pharo-nosql/pharo-ejdb/workflows/Build/badge.svg?branch=master)](https://github.com/pharo-nosql/pharo-ejdb/actions?query=workflow%3ABuild)
[![Coverage Status](https://codecov.io/github/pharo-nosql/pharo-ejdb/coverage.svg?branch=master)](https://codecov.io/gh/pharo-nosql/pharo-ejdb/branch/master)

[![Pharo 11](https://img.shields.io/badge/Pharo-11-%23aac9ff.svg)](https://pharo.org/download)

Install
-------

### Building EJDB library

- You need to download the library sources and compile it for your platform, from here: https://github.com/Softmotions/ejdb
- You can place it along with your image or with your VM plugins

### Installing pharo-ejdb in your image
Then, you can install it executing:

```Smalltalk
Metacello new 
	repository: 'github://pharo-nosql/pharo-ejdb';
	baseline: 'EJDB';
	load.
```
