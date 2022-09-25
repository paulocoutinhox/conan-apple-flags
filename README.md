# Conan Apple Flags

This is a test project to test Apple flags with Conan.

<p align="left">
    <a href="https://github.com/paulocoutinhox/conan-apple-flags/actions/workflows/ios.yml"><img src="https://github.com/paulocoutinhox/conan-apple-flags/actions/workflows/ios.yml/badge.svg"></a>
</p>

## How to build for iOS

Execute on terminal:

`make ios`

## Tree

This is the project structure when run `make tree`:

```
.
├── CMakeLists.txt
├── Makefile
├── README.md
├── conan
│   ├── profiles
│   │   └── ios_profile
│   └── recipe
│       └── conanfile.py
├── include
│   └── hello.h
├── requirements.txt
├── src
│   └── hello.cpp
└── test_package
    ├── CMakeLists.txt
    ├── conanfile.py
    └── src
        └── example.cpp

7 directories, 11 files
```
