# CMake Notes

Check to see if installed: `cmake --version`

Install: `sudo apt install cmake`

## CMake on Linux with VSCode
[VSCode + CMake](https://code.visualstudio.com/docs/cpp/cmake-linux)

## VSCode Commands 
1. Create a CMake Project: `Ctrl+Shift+P` then `CMake: Quick Start`
  * Enter name of project - written to **CMakeLists.txt**
2. Select as executable (main.cpp) or library (.cpp and .h)
3. Select a kit (compiler toolchain) and variant
  * variants can be: *Debug*, *Release*, *MinRelease*, *RelWithDebInfo*
4. Run `Ctrl-Shift-P` then `CMake: Configure` to generate build files in build folder
5. Run `CMake: Build` to build the project (or click build in Status bar)
6. Run `CMake: Debug` to run the debugger

See [Documentation](https://github.com/microsoft/vscode-cmake-tools/tree/main/docs#cmake-tools-for-visual-studio-code-documentation)