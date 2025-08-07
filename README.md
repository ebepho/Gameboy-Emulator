Gameboy Emulator

A simple Gameboy emulator written in C.

## Build Instructions

Follow these steps to build and run the project:


```bash
cd Gameboy
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
./Gameboy
```

## Project Structure
```
Gameboy/
├── include/
│   └── context.h
├── src/
│   ├── context.c
│   └── main.c
├── build/ (generated)
├── CMakeLists.txt
└── README.md
```
