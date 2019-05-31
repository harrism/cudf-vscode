# cudf-vscode
Visual Studio Code configuration files for developing [RAPIDS cuDF](https://github.com/rapidsai/cudf). 

## Installation

One or more of the following:
 - Copy the the contents of the `.vscode` directory into your `cudf/.vscode` directory. 
 - Manually merge part or all of the the files in `.vscode` into your Visual Studio code configuration for cuDF.

## Included

 - `tasks.json`: Configurations for build and test tasks.
 - `launch.json`: Configurations for launching the debugger with libcudf gtests and other launch configurations.
 - `c_cpp_properties.json`: Configuration for C++ intellisense in the Microsoft VSCode C/C++ extension. Includes header file search paths.
