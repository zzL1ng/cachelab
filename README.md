# Cachelab

## usage

Clone or download this folder to your Linux system, then you can `make` in this folder to debug your own code. (AC code provided)

## requirements

gcc

python2 (This is IMPORTANT, for the `driver.py` was made by Python 2.x. If you don't want to change the Python version, refactoring is needed.)

valgrind (Dependency of `.trace` files)

## test

### csim-def

Use `./csim-def -v -s <num> -E <num> -b <num> -t <path_to_trace>`.

### csim

This line is used to test your own-written function with your own parameters.

Use `./csim -s <num> -E <num> -b <num> -t <path_to_trace>`.

### test-csim

Use `./test-csim`.

### test-trans

M, N are describing size of the matrix.

Use `./test-trans -M <num> -N <num>`.

## Evaluate

Use `./driver.py`. It will start evaluating automatically.

