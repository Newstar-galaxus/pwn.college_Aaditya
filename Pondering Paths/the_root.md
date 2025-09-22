# Challenge Name
Launch a terminal and invoke the pwn program using its absolute path

## My solve
**Flag:** `pwn.college{g1_tUZb9X9pdG-TASqbhpgNeMu9.QX4cTO0wSO5gjNzEzW}`

type in your solve and your thought process behind solving the challenge. Include as much as info as possible. Use triple ticks for bash.
```bash
I understood that there's a file system that starts with / and the program is pwn in this case, and I typed /pwn
```

## What I learned
The filesystem starts at /
Under that, there are other directories, configuration files, programs, and flags
You can invoke a program by providing its path on the command line
In this case, I gave the exact path, starting from /, so the path is /pwn
This style of path, one that starts with the root directory, is referred to as an "absolute path"

## References 
N/A
