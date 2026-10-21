# C++ File Access Control System

A C++ project that manages users, files, and file access permissions using an Access Control List (ACL) structure.

## Features

- User management
- Add and list users
- File creation
- Filename validation
- List registered files
- Store user permissions using maps and sets
- Object-oriented design with separate classes

## Project Structure

| File | Description |
|---|---|
| `main.cpp` | Program entry point |
| `FileACL.h` | Defines the file access control structure |
| `UserManager.h` | Declares the UserManager class |
| `UserManager.cpp` | Implements user management functions |
| `FileManager.h` | Declares the FileManager class |
| `FileManager.cpp` | Implements file management functions |

## Technologies

- C++
- C++17
- Standard Template Library (STL)
- `std::filesystem`

## How to Compile

Compile the project using GCC:

```bash
g++ -std=c++17 main.cpp UserManager.cpp FileManager.cpp -o main.exe
```

Run the program on Windows:

```powershell
.\main.exe
```

## Current Status

Work in progress.


