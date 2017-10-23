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
