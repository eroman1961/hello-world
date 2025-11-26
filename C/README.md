# hello-world (C)

This folder contains a minimal C program that prints "Hello, world!".

Files
- `main.c` — simple program using `printf`.

Build & run (bash / WSL)

Using GCC:
```bash
cd c
gcc -o hello main.c
./hello
```

Notes
- If you don't have a C compiler installed, install one of:
  - `gcc` via your distribution's package manager (e.g., `apt install build-essential`, `dnf install gcc`)
  - For Windows users, run these commands under WSL or another Unix-like environment.

Expected output:
```
Hello, world!
```
