This repo contains my work for CS170 (Operating Systems) at UCSB, taught by Rich Wolski W26.

Since this is coursework tied to an active class, the professors have asked that the code not be made public. Because of that, this repo does not share the code and the actual implementation isn't shared here.

What the project is: KOS is a small operating system built to run on a simulated MIPS machine. Over the course of the quarter it grows from handling basic I/O (reading and writing to a console) into supporting multiple processes running at the same time, things like fork and exec, and eventually pipes between processes. It's meant to teach how a real OS manages a CPU, memory, and devices by actually building a (very stripped down) one from scratch.

It's built around the MIPS R3000 processor.

The simulator mimics a real MIPS R3000 CPU closely enough that it can actually run binaries compiled for that hardware.
It's a 32-bit machine, so pointers and integers are both 4 bytes (doubles need 8-byte alignment).
Since nobody has an actual MIPS/Ultrix box lying around to compile on, you cross-compile your test programs on a regular Linux/Intel machine using a special GCC cross-compiler targeting decstation-ultrix, then load the resulting binary into the simulator to run.

If you are interested in seeing the code, feel free to email me at abhiduttaca@gmail.com.
