CHIP-8 Emulator

A simple CHIP-8 emulator written in C.

## Build Instructions

Follow these steps to build and run the project:


```bash
cd CHIP-8
```
```bash
mkdir -p build && cd build
```
```bash
cmake ..
```
```bash
make
```
```bash
./Chip8
```

## Project Structure
```
CHIP-8/
├── include/
│   └── context.h
├── src/
│   ├── context.c
│   └── main.c
├── build/ (generated)
├── CMakeLists.txt
└── README.md
```