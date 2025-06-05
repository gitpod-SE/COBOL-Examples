## COBOL Examples 
This is a collection of example and test COBOL programs I've written. I'm currently in the process of updating 
each folder with a README.md file and more comments so that the examples are easier to follow along with.

All program were written using [GnuCOBOL](https://gnucobol.sourceforge.io/) in Linux.  

## Development Environment

This repository is configured with a devcontainer that includes:
- GnuCOBOL compiler and runtime
- Required libraries for COBOL development
- VS Code extensions for COBOL syntax highlighting and language support

### Compiling and Running COBOL Programs

To compile a COBOL program:
```bash
cobc -x program.cbl
```

To compile and run in one step:
```bash
cobc -x program.cbl && ./program
```

For free-format COBOL:
```bash
cobc -x -free program.cbl
```

### Note on Terminal-Based Programs

Some examples use terminal-based display features that require a proper terminal environment. These may not work correctly in all environments.



