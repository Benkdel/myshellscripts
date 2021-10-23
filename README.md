# this repository contains helper scripts for holberton school projects

**1. c basic file generator with betty style**
- Copy the file into a folder included in your $path directory so it can be use from everywhere
- Run the file in your shell. i.e: $ cfilegen   - then enter values requested

find command to change several files extension:
find . -type f -name "*.o" -exec sh -c 'mv "$1" "${1%.o}.c"' _ {} \;

