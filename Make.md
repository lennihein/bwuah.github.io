## OP Makefile

#### Installation

```bash
wget "bwuah.github.io/makefile"
```

or <a href="bwuah.github.io/makefile">download</a>

#### Features

- Automatically fetches all C sourcefiles, including headers.

- Edit to specify a Folder to Build into, standard `build`

- Edit to include libraries

- Edit to add Compilerflags or change Compiler

- Build and Run
```bash
make
```

- Remove all .o Files and Executables
```bash
make clean
```

- Build and run with Valgrind
```bash
make v
```

#### Issues

- when using the Build-Directory Mode, every make will compile the exe from the .o files, for some reason.
- some command chains can invoke shell error messages appearing, though not limiting functionality, it's not pretty.