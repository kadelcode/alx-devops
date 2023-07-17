Create a script that prints all possible combinations of two letters, except ```oo```.
- Letters are lower cases, from ```a``` to ```z```
- One combination per line
- The output should be alpha ordered, starting with ```aa```
- Do not print ```oo```
- Your script file should contain maximum 64 characters
```
julien@ubuntu:/tmp/0x03$ echo $((26 ** 2 -1))
675
julien@ubuntu:/tmp/0x03$ ./12-combinations | wc -l
675
julien@ubuntu:/tmp/0x03$ 
julien@ubuntu:/tmp/0x03$ ./12-combinations | tail -303 | head -10
oi
oj
ok
ol
om
on
op
oq
or
os
julien@ubuntu:/tmp/0x03$
```
