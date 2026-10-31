# CHIP-8 Emulator

A CHIP-8 emulator written in modern C++23, built with CMake and SDL2.

## Build

```
cmake -S . -B build -G Ninja
cmake --build build
./build/chip8
```

## Status

- [x] Project skeleton
- [ ] Memory, registers, stack
- [ ] Opcode decoding and execution
- [ ] Display (SDL2)
- [ ] Keyboard input
- [ ] Timers and sound
