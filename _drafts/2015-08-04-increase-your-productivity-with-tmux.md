---
layout: post
title: Increase your terminal productivity with tmux
tags: programming linux terminal
excerpt: Tmux is a terminal multiplexer that can help you be more productive when using the terminal. The tmux config I'm presenting here has some nifty features that make it more suitable for pair programming
comments: true
---

A good way to become more productive on your Mac or Linux system is to get familiar with the terminal and applications that come along with it. [Tmux](https://tmux.github.io/), a terminal multiplexer, allows you to get the most out of your terminal. 

If you are familiar with [GNU Screen](https://www.gnu.org/software/screen/) you can think of tmux as an easier-to-use and a little more powerful alternative to Screen. 

Tmux allows you create sessions in your terminal that you can persist and re-attach to at any later point in time. Think about ssh-ing into a server and wanting to come back later to where you left off. Tmux also gives you the option to create multiple windows (think tabs) and panes (split screens) within your terminal. This allows you to organize your terminal workspace and create and arrange individual workspaces.

![Tmux in action](/assets/img/uploads/tmux.png)

But what's the fuzz all about? iTerm supports tabs and panes, Gnome Terminal supports tabs as well, why would anyone feel the urge to learn some archaic technology in this day and age?

## Tmux vs Terminal Emulators
- session persistence
- platform independent, mac and linux
- works on remote machines, servers, raspberry, beaglebone
- looks sleek
- customizable

## Customizations, a very basic config
- change modifier key binding (C-a)
- caps lock -> ctrl
- split windows vertically, horizontally
- get started from here, add your own modifications by research

## The problem with over-customizing
There are basically two schools of thought out there. Those who customize the shit out of their environment and those who try to keep it basic. I think the truth lies somewhere in between. Sure, customizing your command line tools like tmux (but also bash, zsh, vim, emacs, you name it) can maximize your personal productivity. You can use aliases and custom key bindings to execute some really fancy commands in a wink. Even better: you don't have to memorize all those complex commands and parameters.

The downside becomes apparent when you're working with others. All of a sudden you're used to your heavily customized environment and struggle using anything else. And now think about those poor souls who will find themselves in a situation where they need to use your setup and have to give up on some basic tasks just because your "well-crafted" config is standing in their way. Some of my colleagues are very good at letting me know when my urge to customize my configs is getting out of hand by simply refusing to do pair programming on my machine as long as I dont "fix" something they can't use. And rightly so!

There are lots of heavily modified configs out there (TODO: link awesome vim) that surely are handy when you know how to use them. However, it takes lots of time to learn the ins and outs of those configs and chances are you're never going to use nearly close of all the features those configs will provide.

My advice for you is to start simple and basic. Learn how your tools are meant to be used in their basic configs, find out about their striking downsides and fix them along the way. Feel free to research on more ways to improve and optimize your config but always keep in mind that the next poor soul that feels helpless being confronted with your system might just be sitting next to you. Keep a sane middle ground, try stuff out but make sure that nothing gets in the way of actually using your tools without having to read through 500 lines of manuals and configs first.

## What else?
There are plenty of resources out there, you can find people sharing their dotfiles on Github, read the Pragmatic Press book specifically about tmux. But it's easiest to simply try it for yourself and get started using it.

Find my config on [the next blog post](/2015/08/04/pairing-friendly-tmux-conf.html)