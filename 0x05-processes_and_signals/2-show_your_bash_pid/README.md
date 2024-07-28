Using your previous exercise command, write a Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

Requirements:

- You cannot use ```pgrep```

The third line of your script must be ```# shellcheck disable=SC2009``` (for more info about ignoring ```shellcheck``` error [here](https://github.com/koalaman/shellcheck/wiki/Ignore))
```
sylvain@ubuntu$ sylvain@ubuntu$ ./2-show_your_bash_pid
sylvain   4404  0.0  0.7  21432  4000 pts/0    Ss   03:32   0:00          \_ -bash
sylvain   4477  0.0  0.2  11120  1352 pts/0    S+   03:40   0:00              \_ bash ./2-show_your_bash_PID
sylvain   4479  0.0  0.1  10460   912 pts/0    S+   03:40   0:00                  \_ grep bash
sylvain@ubuntu$
``` 
Here we can see that my Bash PID is ```4404```
