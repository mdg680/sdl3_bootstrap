# SDL3 test project.

## Setup

### Dependencies
#### SDL3
Project uses SDL3 and is included in the project via a git submodule and resides in ```./SDL``` from which it is included via CMake

### Build
```sh
cmake -S . -B build # Set source and build dir respectively
cmake --build build # Run the build
```