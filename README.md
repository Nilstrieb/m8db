# m8db

Debugger and interpreter for the M8 pseudo-assembly language. Inspired by `gdb` or `lldb`

More infos: https://github.com/ah1m1/M8NI

Usage: `$ ./m8db (filename)`


# Instructions:  
* `INC r`
* `DEC r`
* `JUMP label`
* `JUMP line`
* `STOP`
* `IS_ZERO r label`
* `IS_ZERO r line`
* `.labelname`

`# anything` is a comment

Where `r` is a register number, `line` is a line number and `label` is a label name.  
`IS_ZERO` jumps to `label` if `r` is zero
