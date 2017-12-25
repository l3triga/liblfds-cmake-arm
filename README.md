# liblfds-cmake-arm
CMake Android armeabi-v7a build of liblfds711 library 

##### Requirements: 
- CMake (version 3.7 or higher)
- Android NDK

##### Instructions
- Update *Toolchain-android-armv7a.cmake* file with path to NDK bundle
- Run following commands in terminal for out-of-source build
```bash
cd build
cmake -DCMAKE_TOOLCHAIN_FILE=../Toolchain-android-armv7a.cmake -DCMAKE_BUILD_TYPE=Release ..
make
```

Static library (.a) will be found in **build** directory
