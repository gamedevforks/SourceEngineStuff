Model loading code for the 2003 source code leak with full support for v35-v36 models and limited support for v37 models.

The `animgroups` and `bonedescs` segments (names could be actually different) of v37 are ignored, and there's no support for shared animation.

Add `public/studio.cpp` to `engine` source files before building.