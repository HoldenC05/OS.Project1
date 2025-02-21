# Kilo.c

Kilo is a small, simple text editor written in C. It is designed to be lightweight and easy to understand.

## Features

- Basic text editing capabilities (insert, delete, save)
- Syntax highlighting for C files
- Search functionality
- Status bar with information about the file and cursor position

## Installation

To compile Kilo, you can use the make command with the included make file


## Usage

You can start Kilo by running the compiled executable with an optional filename:

```sh
./kilo [filename]
```

If a filename is provided, Kilo will open that file. Otherwise, it will start with an empty buffer.

## Controls

- `Ctrl-S` - Save the current file
- `Ctrl-Q` - Quit the editor
- `Ctrl-F` - Find a string in the file
- Arrow keys - Move the cursor
- `Page Up` / `Page Down` - Move the cursor up/down by one screen
- `Home` / `End` - Move the cursor to the beginning/end of the line
- `Backspace` - Delete the character before the cursor

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

Kilo is based on the tutorial here: [LINK](https://viewsourcecode.org/snaptoken/kilo/index.html)