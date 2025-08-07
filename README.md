# Formateur

**C++ has never looked this good.**

Formateur is a stylish and opinionated `clang-format` configuration for modern C++ developers who appreciate clean, consistent, and beautiful code.

##  Why Formateur?

Formatting code is often a mechanical burden that steals mental energy.  
Formateur automates that process — no more debates about braces, spaces, or wrapping.
Just drop in the files and run the included scripts to transform messy C++ into readable, maintainable code ready for human review.

## Included Tools & Scripts

- `.clang-format-cpp` – Config for `.c/.cpp/.cxx/.cc` files  
- `.clang-format-header` – Config for header files  
- `format_code.sh` – Shell script for Unix-like environments  
- `format_code.bat` – Batch script for Windows  
- Bonus: `astyle` configs/scripts (`astyle-cpp.ini`, `astyle-header.ini`, `astyle.exe`) if desired that control statements should be enwrapped with braces

##  Usage

Copy these files to your project, then in your project root:

**On Windows:**
Double-click on format_code.bat

**On Linux/macOS:**
./format_code.sh

## License

This project is released under [CC0 1.0](LICENSE.md). Use it freely.
