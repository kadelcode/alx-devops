# Loops, conditions and parsing
## Background Context


## Resources
**Read or watch:**

- [Loops sample](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_09_01.html)
- [Variable assignment and arithmetic](https://tldp.org/LDP/abs/html/ops.html)
- [Comparison operators](https://tldp.org/LDP/abs/html/comparison-ops.html)
- [File test operators](https://tldp.org/LDP/abs/html/fto.html)
- [Make your scripts portable](https://www.cyberciti.biz/tips/finding-bash-perl-python-portably-using-env.html)

**man or help:**
- ```env```
- ```cut```
- ```for```
- ```while```
- ```until```
- ```if```

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
- How to create SSH keys
- What is the advantage of using ```#!/usr/bin/env``` bash over ```#!/bin/bash```
- How to use ```while```, ```until``` and ```for``` loops
- How to use ```if```, ```else```, ```elif``` and case condition statements
- How to use the ```cut``` command
- What are files and other comparison operators, and how to use them

## Requirements
### General
- Allowed editors: ```vi```, ```vim```, ```emacs```
- All your files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A ```README.md``` file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- You are not allowed to use ```awk```
- Your Bash script must pass ```Shellcheck``` (version ```0.7.0```) without any error
- The first line of all your Bash scripts should be exactly ```#!/usr/bin/env bash```
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Copyright - Plagiarism
- You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
- You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
- You are not allowed to publish any content of this project.
- Any form of plagiarism is strictly forbidden and will result in removal from the program.

## More Info
### Shellcheck
[Shellcheck](https://github.com/koalaman/shellcheck) is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. ```Shellcheck``` is your friend! All your Bash scripts must pass ```Shellcheck``` without any error or you will not get any points on the task.

```Shellcheck``` is available on the school’s computers. If you want to use it on your own computer, here is how to [install it](https://github.com/koalaman/shellcheck#installing).

Examples:

Not passing ```Shellcheck```:
![Not passing shell check](https://github.com/kadelcode/alx-devops/blob/main/0x04-loops_conditions_and_parsing/images/Vxotqyj.png)

Passing ```Shellcheck```:
![Passing shell check](https://github.com/kadelcode/alx-devops/blob/main/0x04-loops_conditions_and_parsing/images/ubHWxDU.png)

For every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code ```SC2034```, you can browse [https://github.com/koalaman/shellcheck/wiki/SC2034](https://github.com/koalaman/shellcheck/wiki/SC2034)
