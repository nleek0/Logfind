# Logfind
This is a functionality similar to grep recreated in C for linux and macos that only searches through C files in a directory where it is run.

## Dependencies
This requires the glob.h library.

## Use
Once the program is compiled, it is run in a directory with the format ```./logfind WORD```.
The program will then display all the files and lines that contain the given word.
