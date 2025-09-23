# Challenge Name
To practice referring to paths using . a bit more and to run it from the /challenge directory.

## My solve
Output:
`hacker@paths~implicit-relative-path:~$ cd /challenge
hacker@paths~implicit-relative-path:/challenge$ ./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{M-DCPLHzfQ_hGWeK7Qwd39fkvps.QXxUTN0wSO5gjNzEzW}`
**Flag:** `pwn.college{M-DCPLHzfQ_hGWeK7Qwd39fkvps.QXxUTN0wSO5gjNzEzW}`

type in your solve and your thought process behind solving the challenge. Include as much as info as possible. Use triple ticks for bash.
```
I understood that linux gives an error "command not found" as a safety measure to not invoke unwanted programs that might have the same name, so I used ./run to specify to linux that I want this specific (program?directory?idk) to be exected
```

## What I learned
If Linux searched the current directory for programs every time you entered a naked path, you could accidentally execute programs in your current directory that happened to have the same names as core system utilities
How to explicitly use relative paths to launch run in this scenario. 
The way to do this is to tell Linux that you explicitly want to execute a program in the current directory, using . like in the previous levels.

## References 
N/A
