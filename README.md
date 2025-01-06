# chadrc
Resource containers for the chads at Infinite Sum Games

# For the Dev, who wanted to be 10x (this is for you)

Common linux commands which are a must use one a day to day basis
0. `cd` - get your ass into that directory
1. `ls` - get your list of files and folders cuz u too dumb to remember them
2. `mkdir` - Create another directory, yep, cuz that's all your ugly ass knows in the name of linux
3. `touch` - Creating files only, don't get the wrong idea :)
4. `rm` - Remove your stupid files and trash-can directories
5. `cp` - Copy pasta programmer
6. `mv` - Move bitch, get outta the way (source -> destination btw)
7. `grep` - too much data, find only what you need (needs pipe btw)
8. `nvim` - Code editor for the Martian Hackers 😏
9. `ssh` - Peeping tom on PORT 22
10. `|` - pipe stuff from one command to another (and they said only python can 
pre-process) 
11. `clear` - clean slate for your terminal
12. `btop` - Monitor your system for gods sakes!!! Check that RAM spike!!!
13. `wget` - Good download utility when your package manager breaks :))
14. `chmod` - give or revoke permissions to programs cuz "no" means yeah baby :)
15. `unzip` - unzip an archive. No one likes things sheathed
16. `tar` - create or extract a tarball (another format of compression)
17. `zip` - zip a bunch of files. (small size matters)
18. `pkill`- Kill a process using process name or pid (graceful shutdown can go 
to hell)
19. `curl` - Make HTTP requests from CLI (nah, use bruno or postman)
20. `which` - Check the installation location of a package (also verify install)
21. `whoami` (if you don't know this, you can go kill yourself)
22. `pwd` - Present-Working-Directory okay!?
23. `sudo` - Super user do (I do as I please, permissions ain't denied for me)
24. `man` - Manual pages ... GPT-kids weak generation, can't handle the chadness of 
these pages. You gotta be a `NeoChad` (the modern-day chad developer who 
idolizes the gigachads from 90s that wrote Unix and Linux)
25. `cal` - Calendar (find your "that time of the month LOL")

### Configs We Installed in Linux

All configs can be found [ here ](https://github.com/IAmRiteshKoushik/dotfiles)

#### 1. `bspwm`
This is the piece of software that provides you with the required environment 
to open any application. Think of this as the base. Technically, we call it 
"window manager" as any application we launch is launched as a "window" and 
this program manages it.

> CONFIGURATION FOUND AT ~/.config/bspwm/bspwmrc

#### 2. `sxhkd` 
This is a helper program for `bspwm`. In-order to trigger different actions 
like 
- Opening a window (say terminal)
- Closing a window
- Toggling in and out of full-screen

All these events are triggered using short-cut keys. `sxhkd` is your config 
file which contains a list of all the short-cut keys and their associated 
actions.

> CONFIGURATION FOUND AT ~/.config/sxhkd/sxhkdrc

#### 3. `alacritty`
We all need a terminal to operate with. There are many different terminals:
- alacritty
- st (suckless terminal)
- kitty
- ghostty
- xterm
- starship
- warp

We all need that blazingly fast terminal, with quality-of-life features, 
crazy performance and coconut-oily smooth experience. That's alacritty folks.

> CONFIGURATION FOUND AT ~/.config/alacritty/alacritty.toml

#### 4. `picom`
 Add transparency and blur effects to any of the components of your system. 
It's just to make things look cool. There is no real utility here. It also 
 (all beautiful things are inefficient)

> CONFIGURATION FOUND AT ~/.config/picom/picom.conf

#### 5. `polybar`
Your top-bar for getting system stats. There are too many default configs 
which can be commented out because the program itself is a bit resource 
intensive. In-case you wish to switch to something simple there is always 
`i3bar` which comes as a separate package. Additionally, there are too many 
unixporn configs where you see people using multiple polybar setup. This is 
aesthetically pleasing but bleeds out RAM as each bar renders separately.

> CONFIGURATION FOUND AT ~/.config/polybar/config.ini

#### 6. `rofi`
The launcher for all your applications. 

> CONFIGURATION FOUND AT ~/.config/rofi/config.rasi
---

> [!TIP]
> All the above tools are full configurable to your liking. Tinker around 
and find out.

## An Anecdote by Ritesh Koushik
> [!INFO]
> A lot of these configurations are written with simplicity and lesser 
RAM consumption in mind. For all the `ricers` out there would wish to 
spend 15-20% or more of your RAM to render a bunch of cool-widgets, this is 
not for you. 
> Quite a lot of these opinions have formed over a period of 2 years where 
I was using a resource constrained system with 6GB RAM and 30 mins of battery 
backup. There might be overkills.
> This configuration is for users who run heavy applications locally. Be it 
Kubernetes cluters, multiple docker containers, simulators, android emulators 
or even heavy JetBrains IDEs (instead of vim/emacs)

A few lines to sum-it-up all:
> 1. Sane defaults over mindless customizations. 
2. Simple is better than "clever".
3. High performance simple components over aesthetic components with piss-poor 
performance. 
4. Sustainability gets work done. Attraction invites alteration. True for 
colors, themes and perhaps people too.
5. If you have taken the time to learn the painful shortcuts of vim, chances 
are that you will be a pretty successful programmer owing to your ability to 
devote time and effort.
