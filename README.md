
peda-mips
====

PEDA-MIPS - Python Exploit Development Assistance for GDB

CHANGED BY https://github.com/alset0326/peda-arm


## Key Features:
* Just support all commands on original PEDA (except the part of shellcode)
* Use `help peda` to show all the peda help

## Updated Features:
* Add source code context (if it has source code)
* Add system call detect
* Support MIPS style jump instructions (b*/cbz) detect
* Support full arm/thumb assemble
* Add plugin framework. Now you can write your own plugins easily based on peda command
* Add multiple welcome logos (Your gdb need to support zlib)
* Enhance display. Make the length of the separation lines auto detect (Image is too large to display. Just find out yourself)
* Support both remote and local debug
* And so many features that I don't remember

## Installation

```
    git clone https://github.com/mutepigz/peda-mips.git ~/peda-mips
    echo "source ~/peda-mips/peda-mips.py" >> ~/.gdbinit
    echo "DONE! debug your program with gdb and enjoy"
    echo "If you have any suggestions please leave me a message"
```

***Tips: These features are also supported on [my own peda repo](https://github.com/alset0326/peda)***
