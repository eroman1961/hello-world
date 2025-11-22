# hello-world (C)

This folder contains a minimal C program that prints "Hello, world!".

Files
- `main.c` — simple program using `printf`.

Build and run (Windows)

Using GCC (MinGW / MSYS2):
```powershell
cd c
gcc -o hello.exe main.c
.\hello.exe
```

Using Microsoft Visual C++ `cl` (Developer Command Prompt):
```powershell
cd c
cl /Fehello.exe main.c
.\hello.exe
```

Notes
- If you don't have a C compiler installed, install one of:
  - MinGW-w64 (via MSYS2) — https://www.msys2.org/
  - GCC for Windows (MinGW installers)
  - Visual Studio (Desktop development with C++) which includes `cl` and the Developer Command Prompt
- On Windows you may need to open the appropriate developer shell (e.g., "x64 Native Tools Command Prompt for VS") to use `cl`.

Expected output:
```
Hello, world!
```
