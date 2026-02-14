# Fortran Programming Teaching Repository

A structured collection of Fortran examples for learning and teaching modern Fortran (Fortran 90/95/2003/2008).


## Repository Structure

fortran-teaching-repo/
01_basics/           Hello World, variables, data types
02_control_flow/     IF/ELSE, DO loops, SELECT CASE
03_arrays/           1D/2D arrays, array operations
04_procedures/       Subroutines and functions
05_io/               File input/output
6_modules/          Modules and USE association
```

---

## Getting Started

### Prerequisites

Install a Fortran compiler. GNU Fortran (gfortran) is recommended:

```bash
# Ubuntu/Debian
sudo apt install gfortran

# macOS (Homebrew)
brew install gcc

```

### Compiling & Running

```bash
gfortran -o program.exe program.f90
./program
```

---

##  Topics Covered

 Folder                   Topics

01_basics          Hello World, variables, constants, arithmetic, intrinsic functions |
02_control_flow    IF/ELSE IF/ELSE, logical operators, DO loops, WHILE loops, SELECT CASE |
03_arrays          1D & 2D arrays, array slices, built-in array functions |
04_procedures      Subroutines, functions, INTENT, OPTIONAL arguments, recursion |
05_io              WRITE/READ, formatted output, file I/O |
06_modules         MODULE, USE, public/private access, shared data |

---

## How to Use This Repo in Class

Each folder has:
- **Source files** (`.f90`) with inline comments explaining each concept
- **A local `README.md`** with learning objectives and exercise prompts

Students can clone the repo and run examples step-by-step:

```bash
git clone https://github.com/PDavies3/Intro_to_FORTRAN.git
```

---

## Exercises

Each module ends with suggested exercises. Solutions are in a `solutions/` subfolder within each topic directory (if provided).

---

## Contributing

Pull requests are welcome. If you'd like to add examples or exercises, please:
1. Follow the existing commenting style
2. Test your code before submitting
3. Add a description to the relevant `README.md`

---

## License

MIT License - free to use, modify, and distribute for educational purposes.
