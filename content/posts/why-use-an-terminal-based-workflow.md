---
title: "Why use an terminal based workflow?"
date: 2021-07-07T20:03:02-03:00
layout: Exploitation
draft: true
---

## Justification

yeah yeah this post is anwser for some friends that asking me "why you work
on terminal?" this question motivate me to write about the beneffits of
works on terminal than using graphical user interfaces(GUI) and a I'll show
some tools that will improve your expirience on linux terminal.

## Why terminal

At the Beginning, we need to remenber the linux philosophy of extensibility.
Once we are using command line interface(CLI) tools, we can integrate them with
another allowing an developer create an intrincated chain of commands to
perform an actions and also can create another chain of commands to filter the
first one output.

This kind of integration allow an developer that knows what they are doing
automate various tasks that in an GUI wouldn't be possible due to its
inflexibility.

For a better understandment, i'll ilustrate what i'm talking about with an
example. Supose that you want to delete 1000... directorys of your pc with an
predefined pattern, you can do it with:
```
rm -rf $(ls | egrep pattern)
```
* rm -rf -> remove all passed directorys
* $()   -> subshell that will execute the command between the parenteses and send to command out of them.
* ls    -> list all directoris
* |     -> send the output of an command to another
* egrep -> will receive an input and and show parts of this input based on predefined pattern 

ps: It's definitivly not a better way to remove directoris, it's just to show the versatility of shell commands

## Terminal Organization

In my opinion, it's one of the best points of working completetly on terminal.
multiple terminal emulator or even another programs that can split the terminal main
window in multiple little terminals allowing one better visualization of
multiple tasks beeing performed at the same time. The gretest example of it is
the tmux that divide de terminal in sessions, panes and sessions as show
bellow:

<!-- ![tmux split screen](images/logo.jpg) -->
It' split terminal window, allow multiple terminal in the same window.

<!-- ![tmux panes](images/tmux_sessions.png) -->
Create new terminal window outside of the first one.

<!-- ![tmux sessions](/images/tmux_sessions.png) -->
Create sessions that comport the panes and splits above mentioned.

## Text edition

The terminal text editor are editors that work in it's own terminal, this
editors are frequently used because they are weightless, had universal presence
on unix like systems and not less importante, each of them had their own
particularities.

For this post, i'll only talk about **VI** like text editors, because i have
more familiarity. **VI** is present by default in the biggest linux
distributions, it's knowed to be much efficient during write process due 
keybindins configurations that allow an development processes without the use o
mouse and custom movimentation. Even work on terminal the lastest version of this 
editors family can use the most recently plugins that GUI editors are using.


# Tasks Management
For managin tasks, i chose an tool called "taskwarrior", this allow me schedule
my weekly tasks.

