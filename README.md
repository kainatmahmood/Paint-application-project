# Paint-application-project
## Overview
This is a C programming project that includes a main program, supporting modules, and a compilation script. The project is designed to be modular and well-organized.

## Features
- Structured code with separate modules
- Uses header files for better readability
- Easy compilation using a batch script

## Installation & Setup
### Prerequisites
- A C compiler (e.g., GCC)
- A terminal or command prompt

### Compilation
To compile the project, run:
```sh
compile.bat
```
Or manually compile using GCC:
```sh
gcc -o main main.c brain/brain.c data/alphabets.c
```

## Usage
Run the compiled program with:
```sh
./main.exe
```

## File Structure
```
PROJECT PF FINAL/
├── main.c         # Main program
├── main.exe       # Compiled executable
├── compile.bat    # Compilation script
├── brain/         # Logic-related files
│   ├── brain.c
│   ├── brain.h
│   ├── brain_header.h
├── data/          # Data handling files
│   ├── alphabets.c
│   ├── alphabets.h
├── .vscode/       # VS Code settings
│   ├── settings.json
```

## How to Contribute
1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

## License
This project is open-source. Feel free to use and modify it with proper credit.

