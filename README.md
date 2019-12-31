[![Build Status](https://travis-ci.org/alhasanmridha/googletest-example.svg?branch=master)](https://travis-ci.org/alhasanmridha/googletest-example)
# googletest-example
A hello world example for googletest framework. Project is created according to [this](https://raymii.org/s/tutorials/Cpp_project_setup_with_cmake_and_unit_tests.html) awsome tutorial. 
## Build
Clone the source code
```bash
git clone https://github.com/alhasanmridha/googletest-example.git
```
googletest libray is added as git submodule. To get googletest source
```bash
git submodule init
git submodule update
```
Now run cmake command to build
```bash
cmake -H. -Bbuild
cmake --build build
```
To see the output
```
./build/test/GoogleTestExample_tst
```
