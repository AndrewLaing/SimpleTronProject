# SimpleTronProject<br />
This project is based around three applications.<br />
SimpleTron, RunSML and SimpleCompiler.<br /><br />

# SimpleTron<br />
The SimpleTron is a machine for entering and running programs written in SML (Simple Machine Language).
SML is a simple low-level language which has similarities with Assembly Languages. 
SML programs are entered into a Virtual Memory space by the user either from the 
keyboard one line at a time, or by loading them from a file with an .sml suffix. 
The SimpleTron allows users to enter, run programs, and write out the contents 
of the Registers and Virtual Memory to the Screen or a Dump File.<br /><br />

# RunSML<br />
RunSML is an implementation of the SimpleTron which allows users to run SML
instructions contained within .sml files from the command line.<br /><br />

# SimpleCompiler<br />
The Simple Programming language is, as its name implies, a very simple programming 
language with a limited set of instructions. It is a subset of the Basic language, 
lacking a lot of Basic’s features.
This Simple Compiler creates files of SML instructions from Simple source files. 
The compiler runs two passes on the Simple source code. On the first pass it 
constructs a lookup table from each line and generates most of the instructions. 
Goto addresses which it could not find in the lookup table during the first pass 
are resolved during the second pass, and the instruction are then written out 
to ‘out.sml’
