# ACA_calculator
Simple calculator using CMake, vcpkg and Qt library. Original example https://doc.qt.io/qt-6/qtwidgets-widgets-calculator-example.html

## build
```
$ cmake -B [build directory] -S . -DCMAKE_TOOLCHAIN_FILE=[path to vcpkg]/scripts/buildsystems/vcpkg.cmake
$ cmake --build [build directory]
```
