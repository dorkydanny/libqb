# QB64

![QB64](source/qb64.png)

# Table of Contents
1. [Installation](#Installation)
    3. [Linux NixOS](#Linux NixOS)

2.  [Usage](#Usage)
3.  [Additional Info](#Additional_Info)

# Installation <a name="Installation"></a>
Download the appropriate package for your operating system. Check the Releases page.

<a name="Linux"></a>
## Linux NixOS
Compile QB64 with ```./setup_lnx.sh```.

Dependencies should be automatically installed. Required packages include OpenGL, ALSA and the GNU C++ Compiler.

<a name="Usage"></a>
# Usage
Run the QB64 executable to launch the IDE, which you can use to edit your .BAS files. From there, hit F5 to compile and run your code.

To generate a binary without running it, hit F11.

Additionally, if you do not wish to use the integrated IDE and to only compile your program, you can use the following command-line calls:

```qb64 -c yourfile.bas```

```qb64 -c yourfile.bas -o outputname.exe```

Replacing `-c` with `-x` will compile without opening a separate compiler window.
