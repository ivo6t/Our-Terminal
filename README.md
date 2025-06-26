# Our Terminal

**Our Terminal** is a retro Soviet-style terminal emulator powered by [Raylib](https://www.raylib.com/).

Type commands like `help`, `rank`, or `status`. Beware of bad talk — the gulag awaits!

Perfect for fans of vintage vibes and meme dev culture.

---

## Features

- Retro Soviet terminal vibe  
- Rank system that evolves based on your productivity  
- Fun "bad talk" detection with gulag punishment  
- Simple command set: `help`, `status`, `clear`, `exit`, `private`, `rank`  

---

## Commands

| Command  | Description                        |
| -------- | ---------------------------------|
| `help`   | Displays available commands       |
| `rank`   | Shows your current rank           |
| `status` | Shows system status               |
| `clear`  | Clears the terminal screen        |
| `exit`   | Closes the terminal               |
| `private`| Enables private mode (no listening)|

---

## Building and Running

### Requirements

- [Raylib](https://www.raylib.com/) installed  
- C compiler (gcc or clang)  
- Code::Blocks or command-line build  

### Build

On **Linux (Arch)**:
```bash
gcc main.c -o our_terminal -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
./our_terminal
