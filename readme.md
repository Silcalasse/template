## Template for C projects
This is a basic template for C projects

In the makefile there are variables
The most important one is SRC, you add all your source files here
they should all be relative to src/
And example hello world file is provided to show you how everything should be set up.

All build objects will be built in build/
And the target is in the root directory.
This makes everything clean and simple
Unlike other prijects where the objects pollute the source tree
This makes it play nice with git

##How to use
Build with make all, or just make
Clean with make clean

