# External Sorting for binary Files

## Overview

This a group project focused on implementing external sorting for binary files. The goal is to efficiently sort large datasets that do not fit into the computer's main memory. External sorting is a technique that involves dividing the dataset into smaller chunks that can fit into memory, sorting those chunks, and then merging them to produce the final sorted output.

- **Ordenation method**: Our choice for external ordenation method was disk merge sort and for internal sort we used quick sort.
- **CSV and binary file handling**: Manipulating data of a csv file in a binary file.
- **Configurability**: The project provides flexibility in configuring parameters such as chunk size, sorting algorithm, and other relevant options.

## How to run it

```
 g++ -Wall ./main.cpp -o exec.exe
./exec
```

## Contributors

[Gabriel Ferreira](https://github.com/Ferreira327)<br>
[Guilherme Azevedo](https://github.com/Gui-L-Azevedo)
