---
title: LPIC 1 - Lesson 2
---

# {{ page.title }}

## it is about 103.1 Work on the command line

we talked about the commands:

```
bash
echo
env
export
pwd
set
```

## exercises

### 1. variable without export

- create a bash variable myname with your firstname as its value
- open a subshell with the command `bash`
- run `echo $myname`, what output do you get?
- run `env|grep myname`, what output do you get?
- exit the subshell with the command `exit`

### 2. variable with export

- create a bash variable myname with your firstname as its value
- export this variable
- open a subshell with the command `bash`
- run `echo $myname`, what output do you get?
- run `env|grep myname`, what output do you get?
- exit the subshell with the command `exit`

### 3. command `set` with globbing and `echo` together with using the wildcard '*'

- cd into homedirectory
- run `echo \.*` , describe what you see and think about what happend
- activate the `noglob` option with the `set` command
- check it with `echo \.*`, describe what you see and think about what happend
- disable `noglob` option with the `set` command


[HOME](https://ogaida.github.io/lpic_1/README.html)