# Challenge Name
To run /challenge/run using a relative path while having a current working directory of /

## My solve
Output:
`hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ /challenge/run
Incorrect...
You invoked this challenge with an absolute path. This challenge needs a relative path!
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{kF9RbMOzzXkTdjUU2a2YNxYJNaG.QX5QTN0wSO5gjNzEzW}`
**Flag:** `pwn.college{kF9RbMOzzXkTdjUU2a2YNxYJNaG.QX5QTN0wSO5gjNzEzW}`

type in your solve and your thought process behind solving the challenge. Include as much as info as possible. Use triple ticks for bash.
```
I understood that the relative path starts with c, which means the relative path is challenge/run
```

## What I learned
If you put in absolute paths everywhere, then it really doesn't matter what directory you are in.
The current working directory does matter for relative paths.
A relative path is any path that does not start at root (i.e., it does not start with /).
A relative path is interpreted relative to your current working directory (cwd).
Your cwd is the directory that your prompt is currently located at.

## References 
N/A
