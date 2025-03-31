# Kilo - A Minimal Terminal Text Editor

Kilo is a lightweight, terminal-based text editor written in C. It provides essential text editing functionalities with a minimalistic design, making it a great starting point for learning about text editor development.

## Features

- Supports basic text editing operations
- Syntax highlighting (if implemented)
- Efficient keyboard-based navigation
- Minimal dependencies
- Runs in the terminal

## Installation

To compile and use Kilo, ensure you have a C compiler (such as GCC) installed on your system.

```sh
# Clone or download the source file
gcc -o kilo kilo.c -Wall -Wextra -pedantic -std=c99
```

## Usage

To start Kilo and open a file:

```sh
./kilo filename
```

### Basic Controls

- **CTRL+Q** - Quit the editor
- **CTRL+S** - Save the file
- **Arrow Keys** - Navigate through the text
- **Backspace/Delete** - Remove characters
- **Enter** - Insert a new line

## Dependencies

Kilo is designed to be lightweight and does not require external libraries apart from standard C libraries.

## Acknowledgments

Kilo is inspired by the original `kilo` text editor created by [Antirez](https://github.com/antirez/kilo), the author of Redis.
