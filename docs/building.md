# Building Lysander Engine

## <u>Getting the Engine</u>

Clone the engine using Git to gain all the engine core files, including LysanderCore and our
CMake-based build system you can read about below.

## <u>Building the Engine</u>
To build the engine we have provided an easy and simple to
use script for Unix shell and Windows Command Prompt.

### Requirements
- CMake version 3.18 or higher
- A CMake compatible C++ compiler
- The cloned copy of Lysander Engine and CMake

### Using the install script
On Windows, simply run the ```build.bat``` script in the root
directory of the cloned engine. This will build the LysanderCore engine
module as a static library in Debug mode you can link to using your C++ compiler and
the ```cmake --build``` command.

To achieve the same on Unix systems compatible with ```sh```, run the ```build.sh```
script included with the engine's root directory. This will build the LysanderCore
library in much the same way as the Batch script for Windows mentioned above.

You may need some libraries or run into issues with CMake building the SFML library, especially
with dependencies.
For more imformation, read the useful page [here](https://www.sfml-dev.org/tutorials/2.6/compile-with-cmake.php)
on the SFML website.
