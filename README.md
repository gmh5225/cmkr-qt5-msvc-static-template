# cmkr-qt5-msvc-static-template

https://github.com/gmh5225/static-build-qt5/releases/download/qt5_5152_static/qt5_5152_static_32.zip

https://github.com/gmh5225/static-build-qt5/releases/download/qt5_5152_static/qt5_5152_static_64.zip

https://github.com/build-cpp/cmkr

https://github.com/build-cpp/Qt5CMakeTemplate


## Building

```
X86
cmake -Bbuild32 -DCMAKE_PREFIX_PATH=c:\Qt\5.15.2\msvc2019static -DCMAKE_INSTALL_PREFIX=install -DCMAKE_CONFIGURATION_TYPES="Release" -AWin32
cmake --build build32 --config Release
cmake --install build32

X64
cmake -Bbuild64 -DCMAKE_PREFIX_PATH=c:\Qt\5.15.2\msvc2019_64static -DCMAKE_INSTALL_PREFIX=install -DCMAKE_CONFIGURATION_TYPES="Release"
cmake --build build64 --config Release
cmake --install build64
```
