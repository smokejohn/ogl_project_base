# Readme

## OpenGL base project using GLFW, GLADE, CMAKE
This base can be used to follow the tutorial for learning OpenGL on <https://learnopengl.com>

### Dependencies
* CMake >= 3.10
* GLFW >= 3.3

GLADE source code is included in this repository (OPENGL 3.3)
if you want you can switch it out for a different version greater than OPENGL 3.3 by generating your own source with the [GLADE webservice](https://glad.dav1d.de). Place the source files into the libs folder (libs/glad)


### Building

execute these commands in the project directory:

```
# create build directory and move to it
mkdir build && cd build

# configure project
cmake ../

# build executables
cmake --build ./
```

The configuration files and the executable will now be in the build folder.
