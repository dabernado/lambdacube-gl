# lambdacube-gl
[![Gitter chat](https://badges.gitter.im/lambdacube3d/lambdacube3d.png)](https://gitter.im/LambdaCube-3D/Lobby)

This is a fork of the Haskell OpenGL backend for LambdaCube 3D, that uses the newer OpenGL 4.3 API instead of OpenGL 3.3. This is a functional port, but largely untested, so you should expect there to be bugs. Nonetheless, you should expect some differences in how your use behaves in comparison to regular LambdaCube 3D code.

## Building instructions

0. On **Linux** install the following libraries.
   i.e. on Ubuntu:
   ```
   sudo apt install libgl1-mesa-dev libxi-dev libxcursor-dev libxinerama-dev libxrandr-dev zlib1g-dev
   ```
   For other Linux distributions make sure the corresponing packages are installed.

   *These libraries required for OpenGL development.*

1. Install Haskell [Stack](http://www.haskellstack.org) by following it's simple [install manual](https://docs.haskellstack.org/en/stable/README/#how-to-install).

2. Checkout the this repository then run the following commands.
```
stack setup
stack build
```
3. Run the examples.
```
cd examples
stack exec lambdacube-gl-hello
stack exec lambdacube-gl-hello-obj
```

## Tutorials and Examples

- [Getting started](http://lambdacube3d.com/getting-started)
- [Workshop material](https://github.com/csabahruska/lambdacube-workshop)
