# Ors-cpp
A hobby programming language

## Building

Requires `nasm` and `ld` on a Linux operating system.

```bash
git clone https://github.com/Oggma/Ors-cpp.git
cd Ors-cpp
mkdir build
cmake -S . -B build
cmake --build build
```

Executable will be `ors` in the `build/` directory.