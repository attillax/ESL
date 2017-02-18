# ESL
Solutions and notes for Trevor Hastie's "The Elements of Statistical Learning" 
book

## How to use Makefile for compilation of the documents
All compiled files are placed in the root directory of the project. 
The LaTeX compilation mistakes (e.g. missed image files) are ignored.

###Available Commands
To compile the file with solutions (ESL_solutions.tex) you will need to execute 
the following command:
```
make
```

To compile the file with notes (ESL_notes.tex) you will need to execute the 
following command:
```
make notes
```

To remove all compiled .pdf you will need to execute the following command:
```
make clean
```

All tex-produced files removed automatically after the compilation
