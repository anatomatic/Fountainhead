Fountainhead
============

Contextual screenwriting environment that leverages the speed of [Sublime Text](http://www.sublimetext.com) and the readability of [Fountain](http://fountain.io), enabling the user to just write.

Inspired by Jonathan Poritsky's [Fountain for Sublime Text](https://github.com/poritsky/fountain-sublime-text) package.

Compatible with Sublime Text [2](http://www.sublimetext.com) and [3](http://www.sublimetext.com/3). Optimized for [Sublime Text 3](http://www.sublimetext.com/3).

## Installation 

### Option A: Package Control
1. Install [Package Control](https://sublime.wbond.net/installation).
2. Select **Package Control: Install Package** from `Tools > Command Palette` (⇧⌘P).
3. Select **Fountainhead**.

### Option B: GitHub
1. [Download the ZIP of this repository](https://github.com/derickc/Fountainhead/archive/master.zip) and uncompress it.
2. Move the uncompressed **Fountainhead** folder to the appropriate packages directory:
    - In Sublime Text, select: `Sublime Text > Preferences > Browse Packages...`
    - Place the **Fountainhead** folder inside the open **Packages** directory.
3. Relaunch **Sublime Text**.

## Quickstart

1. Open your Fountain file.
2. Verify that "Fountainhead" appears in the bottom right-hand corner.
    - If it doesn't, you can click on the offending syntax and change it to "Fountain", or you can use the menu: `View > Syntax > Open all with current extension as > Fountain`.
3. Write!

## Functionality

### Fountain Syntax
The Fountain Syntax is a plaintext markup for screenwriters, invented by John August & Stu Maschiwitz. Take a look at the detailed  [Fountain spec](http://fountain.io/syntax) or check out this handy [cheatsheet](http://fountain.io/_downloads/fountain-reference.pdf).

### Capitalization
On return character elements & sluglines get autocapitalized.

### Smart Line Skipping
Fountainhead is smart about inserting blank lines for the Fountain parser. So if you hit `enter` after a slugline, action, dialogue, transition, or centered text it will add an extra line automatically. But `enter` after a title page Key: Value pair, !Forced Action, ~Lyrics, or a Characther name (with or without @), [[Notes]], ==Synopses, or #Sections — you'll be get a normal single carriage return.

### Page Scroll

## Settings

### How to update settings

## Keybindings (Mac/Windows/Linux)

### Lists
Update your Character and Scene lists from the Command Palette with `Fountainhead: Update ...`
`super + shift + s`  Show Scene List
`super + shift + c`  Show Character List

### Show/Hide Boneyard, Synopses, and Notes
`ctrl + k, ctrl + /`  Toggle Boneyard
`ctrl + k, ctrl + =`  Toggle Synopses
`ctrl + k, ctrl + [`  Toggle Notes

### Text
[Pairs], _Pairs_, *Pairs* all auto-wrap
`super + k, super + u` convert to UPPERCASE
`super + k, super + l` convert to lowercase

### Navigation
 `shift + space` Move the cursor forward (same as right arrow key)  
 `shift + enter` Move cursor down a line (same as down arrow key)  
 `tab` Move outside of notes, parentheticals/parentheses, quotes, and underlined/italic/bold text  
   
---
Feel free to drop me a [line](http://classicblunders.com/contact), or a [dime](https://gratipay.com/derickc/).


