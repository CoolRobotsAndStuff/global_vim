# Global Vim
An i3 config to globally enable vim style keybindings for text editing.

## How it Works

 The config, written purely in the i3 configuration language, serves to mimic vim motions at a global level.
 It works by simulating inputs in your system with the tool of your choice (`xdotool` by default), using the available keybindings for moving the cursor and editing text like the End, Home and arrow keys, ctrl+v, ctrl+c, etc.

This relies on the program that you might be running being able to interpret these hotkeys. Luckily, most do! This way you are able to use vim motions in any program, without having to install any plugins.

## How to use
 To use it, just copy-paste it into your i3 config. It only depends on the `$mod` variable being defined. You can edit the `CONFIG` section in the files to customize them to your liking.

## What are the two files?
The `global_vim_standard` file uses the standard vim keybindings. I haven't tested this standard config thoroughly, because it's not the one I use. If you find any mistakes you can report an issue and I'll fix it. 

The `global_vim_custom` file contains my personal keybindings. It's a good example on how to customize the config. It also includes a way to use double key presses as Escape.

## Editing and adding keybindings

 The fact that it's written as a plain config makes it relatively easy to edit, if a bit repetitive and tedious. This was a fun one-of project, so I'm not planning on adding every single possible keybinding, but you are welcome to add ones that may be missing.
