# GBDK-CMake-Template

## About

This Template

## How to Build?

Just do these commands if it's the first time building it:


```
mkdir build
cd build
cmake ..
make
```

Then if you want to rebuild redo the `make` command **in the `build` folder**.

> [!IMPORTANT]  
> If you've edited `CMakeLists.txt`, is recommended to delete build folder and redo the first steps!

## How to update/change GBDK version?

Edit this line on the `CMakeLists.txt`:

```cmake
set(GBDK_VERSION "4.3.0")
```

> [!IMPORTANT]
> If the target version is less or equal than 4.0, then put a 'v' before the version number.
> e.g GBDK 3.1.1:
> ```cmake
> set(GBDK_VERSION "v3.1.1")
> ```
