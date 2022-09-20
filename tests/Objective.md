# Todo list for changing to Python package

## Python Package

### Goals

- Convert MDB file to zipped CSV file of tables from database
- Use csv tables to create GLM file

## Openfido

### Current Implementation

- CLI

  > openfido run cyme-extract IEEE13.mdb IEEE13.glm

- /usr/local/bin

  - openfido.exe
    - Run command with options as array
  - openfido.py
    - Run main program in cyme-extract with inputs, outputs, and options

- /usr/local/share/openfido/PIPELINE
  - Run main
    - Input list[str] # input file name
    - Output list[str] # output file name
    - Options list[str] #
