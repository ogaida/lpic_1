---
title: LPIC 1 - Lesson 6
---

# {{ page.title }}

## it is about 103.5 Create, monitor and kill processes


- Run jobs in the foreground and background.
- Signal a program to continue running after logout.
- Monitor active processes.
- Select and sort processes for display.
- Send signals to processes.


The following is a partial list of the used files, terms and utilities:

- &
- bg
- fg
- jobs
- kill
- nohup
- ps
- top
- free
- uptime
- pgrep
- pkill
- killall
- watch
- screen
- tmux

## exercises

- what are 3 common ways to let a process run if you logoff? Just tell the commands which will lead you...
- what is the default signal send by kill or killall if you do not change the signal with the -s option?
- what is the standard prefix for screen and what is used for tmux? The standard prefix is used for telling the terminal multiplexer to take the next key stroke as a special command interpreted by the terminal multiplexer, so it does not go to the terminal.
- what to keep in mind if you are using nohup regarding diskspace?
- start a ping process without & and put it to the background. do not forget to pipe the stdout to `/dev/null`. Then get the process back into foreground and put it back into bg. Then kill the process with the kill command

[HOME](https://ogaida.github.io/lpic_1/README.html)