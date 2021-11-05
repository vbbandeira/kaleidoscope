# kaleidoscope

First install LLVM:
```
brew install llvm
```

Then configure the IDE, I suggest VSCode, then with the C++ language files download the language packs and follow the other steps.

In the source code folder type the command below to compile the code:

```
g++ kaleidoscope.cc -o kaleidoscope.bin `llvm-config --cxxflags`
```

After that, type the command below to run the program:
```
./kaleidoscope.bin
```
