## Introduction
This directory contains the code for OCEAN.

## Required Packages
 - g++ (version >= 8)
 - cmake
 - make
 - libgmp-dev
 - libssl-dev  
 - SEAL 3.3.2
 - Eigen 3.3

## Files

In the test-conv in `test/` folder is the convolution from CrypTFlow2.

In the test-relu in `test/` folder is the ReLU from CrypTFlow2.

In the test-reconv in `test/` folder is relu-convolution in FIT.

In the test-ocean in `test/` folder is our relu-convolution of proposed OCEAN.

## Compilation

To compile the library:

```
mkdir build && cd build
cmake ..
make
// or make -j for faster compilation
```

## Running Tests & Networks

In `build/bin/`, run the tests as follows to make sure everything works as intended:

one terminal: `./<test> r=1`

another terminal: `./<test> r=2`


# Credits

This library is developed based on CrypTFlow2 (ACM CCS 2020).

