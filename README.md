Simple tmux project with key bindings. It is window-focused as I use tiling
window manager (i3) and I don't prerer multiple tmux panes opened. What does
this mean?

Imagine vim in the first window, shell in second, server, tests and other
tasks in other windows. And you can (re)start those with F5-F8 keys easily
(like restart server, restart tests suite etc). That's all this does.

Installation
============

Clone this repo and add tixipee command to PATH or create a bash alias.

Usage
=====

Go to a project directory and do

    $ txp -i
    Initialized project configuration in .txp

Now edit the configuration

    $ vim .txp

And then start your project session

    $ txp

Use tmux to do the work, use keybindings C-b F5 - F12 to restart commands 
in windows.

As simple as that.
