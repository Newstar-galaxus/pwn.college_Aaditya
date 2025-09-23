# Challenge Name
type what the challenge asks

## My solve
Output:
`hacker@paths~position-thy-self:~$ /challenge/run
Incorrect...
You are not currently in the /var/log directory.
Please use the `cd` utility to change directory appropriately.
hacker@paths~position-thy-self:~$ cd /var/log
hacker@paths~position-thy-self:/var/log$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{kuZyqC3XhQSekGmY2BH5bVAX1kd.QX2QTN0wSO5gjNzEzW}`
**Flag:** `pwn.college{kuZyqC3XhQSekGmY2BH5bVAX1kd.QX2QTN0wSO5gjNzEzW}`

type in your solve and your thought process behind solving the challenge. Include as much as info as possible. Use triple ticks for bash.
```
I changed the directory to /var/log and then used the challenge run command
```

## What I learned
You can navigate around directories by using the cd (change directory) command and passing a path to it as an argument
This affects the "current working directory" of your process
~ shows the current path that your shell is located at


## References 
N/A
