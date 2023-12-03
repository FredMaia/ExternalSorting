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



# External Sorting for Large Data Sets Project

## Description

## Key Features
- **Efficient Sorting:** Optimized algorithm to minimize the number of read and write operations, ensuring effective performance on large volumes of data.

- **Handling Large Files:** Capability to handle data files that do not fit into main memory, efficiently sorting through sequential read and write operations.

- **Custom Configurations:** Flexibility to configure parameters such as block size for read/write, input/output file paths, among others.

- **Detailed Reports:** Generation of detailed reports on algorithm performance, facilitating analysis and optimization.

## How to Use
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/your-username/external-sorting.git
