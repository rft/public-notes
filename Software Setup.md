#setup #Index 

In this document I just go over the Software that I use across different operating systems. I try to keep consistency between systems so I keep most software the same. However there are always some software exclusive to a certain OS so I have linked those below. 


To keep most of my software consistent I use Nix/NixOS. 

On windows I use NixOS for WSL, so it's pretty much the same experience as linux terminal wise. I do install fd/ripgrep on windows though since I still need to use powershell occasionally. 

MacOS I use nix darwin, so again the terminal experience is essentially the same, minus some packages that don't exist on darwin.

My Linux distro is NixOS, really tuned for productivity, still kind of janky which linux is sometimes. But I really wish I could bring niri to windows/mac since it feels so much better than the way MacOS/Windows handles that. 
# Specific software for OS's 
- [[Linux_Setup]]
- [[Windows Setup]]
- [[MacOS_Setup]]

## Cross platform Software 

### Applications 
Software that I have across all 3 platforms
#### [[VScode]]
Text editor, not always what I use (neovim being the other one), but does excel in certain tasks and there's basically a plugin for everything. 

#### Calibre
What I use to manage books, syncs with my kobo, kind of feels clunky, but I haven't found really anything as featureful and good. 

#### Obsidian
How I manage notes, I used to use orgmode, which I honestly still think is better. However the main issue is mobile, which is where I refer/edit my notes to sometimes. Obsidian does well in this area. But it's also not open source either, so I do want to shift out of Obsidian. At the very least it does use markdown as it's format of choice so I can transfer it elsewhere. 
#### [[Anki]] 
Flashcards, but it's actually pretty goated software, almost like cheating getting information into your brain, although sometimes it does not feel that way. 

#### Netbird 
Like tailscale but open source, that being a VPN that I set up for myself so I can connect to my servers without exposing anything to the scary internet.

### Browsers 
I kind of hate using more than one browser, but sometimes some websites don't work well on firefox based ones (even if I send a chrome useragent) 

I have a list of [[Browser Extensions]] that I use per browser. 


#### [[Floorp]] (Firefox browser) 
Most featureful firefox browser i've found, can even (limitedly) run chrome extensions. 
I use [Natsumi](https://github.com/greeeen-dev/natsumi-browser) which makes my floorp more pretty

#### [[Vivaldi]] (Chromium browser)
Vivaldi is the most featureful chrome browser i've found. There is one part that kind of drives me insane though, which is that when I set up a custom search engine I cannot use \<custom search\> TAB "my search" it's \<custom search\> SPC instead, minor complaint, but I'm so used to the other method for my other browsers that it's engrained into me, and as far as I'm aware I cannot change this behavior. 

#### [[Orion]] (Webkit browser)
I primarily use this on my Mac, 

### Terminal Applications 

#### Atuin
Shell history, shows up as a list \<tab\> to put command down for editing and \<enter\> to run the command. One of my favorites. 
#### Bandwhich 
Like task manager except for network related stuff. Can see what's eating your bandwidth 
#### Bat
an alternative to cat, comes with syntax highlighting and a few other features 
#### Bottom 
View information about cpu, disks, network, memory, etc. An alternative to htop 
#### FFMPEG 
Video tool, can do a ton of different things, I usually use to grab certain things from video files or stitch pictures into a video. But can do a  lot more. 
#### fd
like the `find` command, but I think it has sane defaults. Finds files for you  
#### fzf
fuzzy finder, not too crazy in itself, but works well when mixing the output of other programs to.
#### Git 
Version control, have been considering trying jujutsu though as a new way of managing changes.
#### jq
json processor, though I don't use it as much since xonsh kind of lets me use the python object, for it. Still useful sometimes though 
#### pandoc
Document converter, can convert into a lot of different formats 
#### pass 
Password manager, most useful when setting up environment variables, you can set it to use pass for it. That way I can keep my secrets all in one place, and not completely be scared that I committed something bad. 
#### procs
a `ps` alternative
#### rclone 
pull data from cloud services 
#### rink
Unit converter, based off of frink, but made in rust instead 
#### ripgrep
grep but better pretty much in every way
#### rsync 
sync data across remote machines, done over ssh, slightly slower than rclone, but can do more. 
#### syncthing
File sync between devices
#### tealdeer
man pages but shorter, I prefer to use this first if I just need to get something working quickly. 
#### tio
Serial tty tool
#### tokei 
Count lines of code in a folder, I guess not entirely too useful but it's there 
#### trippy
like traceroute and ping were combined  together 
#### Visidata 
Terminal spreadsheet tool. 
#### watchexec
run commands when files change, like a log or something. 
#### wget
download files from the internet. 
#### yazi 
Terminal file manager 
#### yq 
jq but for yaml 
#### yt-dlp 
tool to download videos, not just youtube though 
#### zellij 
Terminal multiplexer, an alternative to tmux, really nice to use and has more sane defaults.
#### zoxide 
a smarter cd, jumps to a directory based on frequency and some other heuristics, can match partially, very nice program.
#### Neovim 
text editor that I use, used to use emacs, I miss it sometimes, but I got most of the functionality I wanted (I never really used lisp) my configuration is [here](https://github.com/rft/nixcat-nvim)


