# kaleidoscope

First install LLVM and set local variables:
```
brew install llvm
```

Then configure the IDE, I suggest VSCode, then with the C++ language files download the language packs and follow the other steps.

In the source code folder type the command below to compile the code:

```
clang++ -g final-kaleidoscope.cpp `llvm-config --cxxflags --ldflags --system-libs --libs core orcjit native` -o final-kaleidoscope.bin
```

After that, type the command below to run the program:
```
./kaleidoscope.bin
```
