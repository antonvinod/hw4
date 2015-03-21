# GDB Video Tutorial

Intereseted in learning to about GDB? 
Well, you might be interested in this tutorial.
GDB is used amongst professionals, hobbyists and beginning level coders across the globe.
Debugging can be quite labor intensive, luckily GDB can make that struggle a whole lot easier.
In this tutorial we'll go over some basic to advanced debugging techniques using GDB.
I hope in the end you'll find that debugging without GDB to be a thing you once did in the past.

What is GDB
====
Well, GDB is just software you can use to debug your code.
You can use GDB on a number of different languages. 
GDB is used to debug efficiently and professionally.
And it is constantly being maintained and updated.
You can find out more at https://www.gnu.org/software/gdb/

Commands used in Tutorial:
===
There are quite a bit of commands supported by GDB;
 however, we'll use only a select few in the tutorial.
These are all the commands we'll look at in the tutorial.
Keep in mind though, there are a lot more. 

| Commands(Alias)| Example | Description |
|:-----------:|:--------------:|:----------------------------:|
| `quit(q)` | `(gdb)` q | used to quit gdb|
| `delete` | `(gdb) d `| used to delete breakpoints|
| `continue(c)`|`(gdb) c`| continue running program|
| `run(r)`  | `(gdb) r`    | runs gdb on the given file |
| `list(l)` | `(gdb) l`    | lists 10 lines by default  |
| `print(p)`| `(gdb) p i ` | print a variable, where i is the variable|
| `list(l)` | `(gdb) l f(x)`| lists lines centered around function f(x)|
| `watch` | `(gdb) watch var` | prompts user when watch var has changed|
| `set var` | `(gdb) set var x = #` | Sets variable x to value right of `=`|
| `backtrace(bt)`| `(gdb) bt` | |outputs summary of calls to current location|
| `list(l)` | `(gdb) l 20` | lists lines centered around #,where # is a line number |
|`set follow-fork-mode`| `(gdb)set follow-fork-mode w`| follow `w` process, `w` is (child/parent)|


GDB Introduction
----------------
In this introduction video, we'll go over setting up GDB, as well as using some very

<a href="https://www.youtube.com/watch?v=ufHO5rV3E24" target="_blank"><img src="https://i.ytimg.com/vi/ufHO5rV3E24/1.jpg?time=1426804289907" 
alt="GDB_Intro" width="480" height="280" border="10" /></a>


GDB with fork()
---------------

