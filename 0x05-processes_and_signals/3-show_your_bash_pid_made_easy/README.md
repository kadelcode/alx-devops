Write a Bash script that displays the PID, along with the process name, of processes whose name contain the word ```bash```.

Requirements:

-  You cannot use ```ps```
```
sylvain@ubuntu$ ./3-show_your_bash_pid_made_easy
4404 bash
4555 bash
sylvain@ubuntu$ ./3-show_your_bash_pid_made_easy
4404 bash
4557 bash
sylvain@ubuntu$
```
Here we can see that:

-  For the first iteration: ```bash``` PID is ```4404``` and that the ```3-show_your_bash_pid_made_easy``` script PID is ```4555```
-  For the second iteration: ```bash``` PID is ```4404``` and that the 3-show_your_bash_pid_made_easy script PID is ```4557```
