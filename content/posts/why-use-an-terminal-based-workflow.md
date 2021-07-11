---
title: "Why use an terminal based workflow?"
date: 2021-07-07T20:03:02-03:00
layout: Exploitation
draft: true
---

## Introduction

My friends frequently asking me "why you use terminal as a place to
development ?" this question motivate me to write about so many peaple prefer
works on terminal than in a graphical user interface(GUI).

## Extensibility

At the Beginning, we need to remenber the linux philosophy of extensibility.
Once we are using an command line interface(CLI) tool on linux, we can
integrate them with another allowing an developer create an intrincated chain
of commands to perform an actions and also can create another chain of commands
to filer the first one output.

This kind of integration allow an developer that know what they are doing
automate various tasks that in an GUI wouldn't be possible due to its
inflexibility.

## Organization

In my opinion, it's one of the best points of working completetly on terminal.
multiple terminal emulator or even another programs can split the terminal main
window in multiple little terminals allowing one better visualization of
multiple tasks beeing performed at the same time.

In my opinion, the gretest example of it is the tmux that until divide de
terminal in sessions, panes and sessions as show bellow:

![tmux split screen](~/Pictures/logo.jpg)
It' split terminal window, allow multiple terminal in the same window.

![tmux panes](~/Pictures/tmux_sessions.png)
Create new terminal window outside of the first one.

![tmux sessions](~/Pictures/tmux_sessions.png)
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
family of editors can use the most recently plugins of the GUI editors using 
the lSP servers.

