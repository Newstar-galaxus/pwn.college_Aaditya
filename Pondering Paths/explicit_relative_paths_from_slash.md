# Challenge Name
To run /challenge/run using a relative path while having a current working directory of / and use . in relative path

## My solve
Output:
`hacker@paths~explicit-relative-paths-from-:/$ cd /
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
pwn.college{c5c0OclPcJ1tEadZR_POLQVm7Xd.QXwUTN0wSO5gjNzEzW}`
**Flag:** `pwn.college{c5c0OclPcJ1tEadZR_POLQVm7Xd.QXwUTN0wSO5gjNzEzW}`

type in your solve and your thought process behind solving the challenge. Include as much as info as possible. Use triple ticks for bash.
```
I understood that adding ./ any number of times lets the directory remain the same, be it absolute or relative.
```

## What I learned
In most operating systems, including Linux, every directory has two implicit entries that you can reference in paths: . and .. 
The first, ., refers right to the same directory

## References 
N/A
