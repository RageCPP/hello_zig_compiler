# hello_zig_compiler

这是学习使用`zig c++`交叉编译C++的学习项目。

来自: https://github.com/mrexodia/zig-cross

使用方法:
```bash
cmake -B ./build-aarch64-macos -G Ninja -DCMAKE_TOOLCHAIN_FILE=cmake/zig-toolchain-aarch64-macos.cmake
cmake --build build-aarch64-macos/
...
```
