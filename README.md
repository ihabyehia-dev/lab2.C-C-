# C++ Lab - Credit Card Class and C-String Helpers

A small C++ exercise with a test program that constructs credit card objects.

## Files
- `main (1).cpp` - creates and displays three example card objects
- `cstr.cpp`, `cstr.h` - helper routines for C-style strings
- `CC.cpp`, `CC.h` - the credit card class used by the test program
- `reflect (1).txt` - reflection

## Before compiling
The missing `CC.h` and `CC.cpp` have now been restored and their display-method typos corrected. Compile the complete test with:

```bash
g++ -std=c++11 -Wall -Wextra "main (1).cpp" CC.cpp cstr.cpp -o card-test
./card-test
```

Use fictional card numbers only.

The source is preserved as a coursework record; no real credit card details should be stored here.
