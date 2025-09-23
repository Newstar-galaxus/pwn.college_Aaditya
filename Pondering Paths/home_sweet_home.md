# Challenge Name
To figure out the argument where /challenge/run will write a copy of the flag to any file I specify as an argument on the commandline with given constraints

## My solve
Output:
`hacker@paths~home-sweet-home:~$ /challenge/run ~/a
Writing the file to /home/hacker/a!
... and reading it back to you:
pwn.college{Is8TSE8MinT313H0ZNYqJUuPmmq.QXzMDO0wSO5gjNzEzW}`
**Flag:** `pwn.college{Is8TSE8MinT313H0ZNYqJUuPmmq.QXzMDO0wSO5gjNzEzW}`

type in your solve and your thought process behind solving the challenge. Include as much as info as possible. Use triple ticks for bash.
```
I understood that in this challenge, /challenge/run will write a copy of the flag to any file I specify as an argument on the commandline wit given constraints
So I adhered to the contraints and gave the argument ~/a which is a file inside the /home/hacker directory and before expansion is 3 characters
When the command wrote a copy of the flag on the argument (file location?) it (for some reason?) gave me the flag
```

## What I learned
Every user has a home directory, typically under /home in the filesystem. 
In the dojo, I am the hacker user, and my home directory is /home/hacker. 
The home directory is typically where users store most of their personal files.
The ~ in this prompt is the current working directory, with ~ being shorthand for /home/hacker. 
Bash provides and uses this shorthand because, most of my time will be spent in my home directory. 
Whenever bash sees ~ provided as the start of an argument in a way consistent with a path, it will expand it to my home directory.
The expansion of ~ is an absolute path, and only the leading ~ is expanded. This means, for example, that ~/~ will be expanded to /home/hacker/~ rather than /home/hacker/home/hacker.
cd will use your home directory as the default destination


## References 
N/A
