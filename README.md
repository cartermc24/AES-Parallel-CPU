# AES-Parallel-CPU
Simple AES-256 implementation in standard C using PThreads

Change the RUNNING_THREADS variable to control how many threads are run on the CPU.

When running the tool, the first argument must be either ‘a’ or ‘h’ which indicates whether the input file should be read as ASCII values or as hex data.  The second parameter is the input file, the third parameter is the keyfile, and finally the last parameter is the output file.

This code is licensed under the MIT license and may be used under the terms of the license.  Attribution is required.