# Docker for C

This has a basic setup for doing stuff in C.
A basic run command to mount the current directory and do stuff in the terminal is:

    $ docker run --rm -it -v $(pwd):/workspace -w /workspace --cap-add=SYS_PTRACE --security-opt seccomp=unconfined menglewis/clang
