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

In the test-conv in `tests/` folder is the convolution from CrypTFlow2.

In the test-relu in `tests/` folder is the ReLU from CrypTFlow2.

In the test-reconv in `tests/` folder is relu-convolution proposed in FIT (IEEE S\&P 2024).

In the test-ocean in `tests/` folder is our relu-convolution of proposed OCEAN.

## Compilation

To compile the library:

```
mkdir build && cd build
cmake ..
make
// or make -j for faster compilation
```

## Running Tests

In `build/bin/`, run the tests as follows:

In one terminal: `./<test> r=1`, and in another terminal: `./<test> r=2`


# Credits

This library is developed based on CrypTFlow2 (ACM CCS 2020).

