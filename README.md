# ECShell
An embedded shell implementation for MCUs based on ECLayer.

Based on following libraries:

- [ECLayer](https://github.com/eggcar/ECLayer "ECLayer@Github") by Eggcar, A stand-alone POSIX-like vfs abstract layer for ARM Cortex-M series

- [avlhash](https://github.com/skywind3000/avlmini "avlmini@Github") by skywind3000, AVL implementation which is as fast/compact as linux's rbtree

- [LineNoise](https://github.com/antirez/linenoise "LineNoise@Github") by Salvatore Sanfilippo, A small self-contained alternative to readline and libedit 

- [optparse](https://github.com/skeeto/optparse "optparse@Github") by skeeto, Portable, reentrant, getopt-like option parser 

I modified linenoise to fit ECShell and ECLayer implementation, and rewrite the linenoise 'history' with ring-buffer.

More introduction and sample code will be updated later...
