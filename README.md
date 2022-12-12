# nns-speedup-optimization

Final project for Multicore Programming 2022 in SYSU.

## Description

- Implement 14 different approaches to optimize Nearest Neighbor Search.

- 1 CPU version and 8 GPU versions were implemented using Linear Search.

- 1 CPU version and 1 GPU version using KD-Tree.

- 1 CPU version and 1 GPU version using Octree.

## Code Information

- ./main.cu: CUDA main file.

- ./core.cu: various optimization versions.

- ./utils.h: some common library functions.

## Compile Instruction

```bash
$ nvcc -Xcompiler -fopenmp -arch=sm_70 main.cu -o main
$ ./main
```
