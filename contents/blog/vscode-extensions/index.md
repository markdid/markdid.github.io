---
title: My Favorite VS Code Extensions of 2022
date: 2022-03-14
template: blog
image: ./vs_header.jpg
banner: ./vs_header.jpg
description: 
---

Cover Photo by [Gabriel Heinzer](https://unsplash.com/photos/EUzk9BIEq6M)

I use VS Code for just about everything working as a web developer, mobile applications developer, and most recently as an embedded systems developer working in C.

Here are some are my favorite extensions I use to make my vs code look the way I want and make my life a little easier.

1\. [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
----------------------------------------------------------------------------------------------------------------------

This extension makes it easy to see at a glance the context I’m in by

Available [here](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) or install directly by opening vs-code, type Ctrl+p then paste `ext install CoenraadS.bracket-pair-colorizer-2`

![](https://miro.medium.com/max/1400/1*ioGOnjNJMLidmnWWmIADHw.png)
Screenshot from marketplace.

2\. [Atom One Dark Theme](https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark)
----------------------------------------------------------------------------------------------------------

I’ve tried plenty of themes and color schemes but the Atom One Dark theme is my favorite because the colors have useful contrast and look great.

![](https://miro.medium.com/max/1400/1*Dk82tQgYBZuFrzpK_03rtA.png)![](https://miro.medium.com/max/896/1*vX9tq7aRlbVUApOrSS9e8A.png)![](https://miro.medium.com/max/960/1*dn_KUtTvNLADyruOpkLrEg.png)
Sample React code before/after theme

Install with `ext install akamud.vscode-theme-onedark`

[3\. VSCode Great Icons](https://marketplace.visualstudio.com/items?itemName=emmanuelbeziat.vscode-great-icons)
---------------------------------------------------------------------------------------------------------------

Slightly less popular than the most common icon extension [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons) but my personal favorite. I think the icons here look so much better than the default and the folder icons make it easier to tell the directory I’m in.

![](https://miro.medium.com/max/608/1*6gFtK2wGg-JEQhbxqrCeBA.png)![](https://miro.medium.com/max/356/1*s_szysZs0BYuZ7sZB5Km5w.png)

Install with `ext install emmanuelbeziat.vscode-great-icons`

[4\. Hungry Delete](https://marketplace.visualstudio.com/items?itemName=jasonlhy.hungry-delete)
-----------------------------------------------------------------------------------------------

Pretty simple but very convenient. This is helpful when deleting a few empty lines by getting rid of all the whitespace. Saves me from having to select multiple lines or using ctrl-backspace since getting rid of extra whitespace is something that happens pretty frequently

![](https://miro.medium.com/max/992/1*lMBDOkbJ6HFGi1JHfV838Q.gif)

Moving the catch to the top only takes one ctrl-backspace. Gif taken from extension listing.

`ext install jasonlhy.hungry-delete`

[5\. Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
--------------------------------------------------------------------------------------------

This one is just for web developers but super easy for static and dynamic pages. Most useful because it auto reloads when changes are made.

![](https://miro.medium.com/max/1400/1*8KDtBh4cTE1yT4NuzXCdAQ.gif)
Auto-reload feature. Gif taken from extension listing.

`ext install ritwickdey.LiveServer`

[6\. TabOut](https://marketplace.visualstudio.com/items?itemName=albert.TabOut)
-------------------------------------------------------------------------------

Like Hungry Delete this is a handy little keybinding that gets your cursor out of parentheses, quotes, and brackets with a tab. I find this useful since VSCode auto-completes these for you you can press tab instead of going to the arrow keys.

`ext install albert.TabOut`

7\. Snippets
------------

If you don’t know about snippets you should because they’re super helpful when there are blocks of code you tend to repeat in a language.

Snippets are small preprogrammed strings from an extension or that you write yourself that autocomplete to larger blocks of code. I find this especially useful when creating React components where a lot of the boilerplate code gets repetitive.

![](https://miro.medium.com/max/1400/1*aMZqQhTtC7Ru_RCxhtcOvQ.png)
Some of the snippets that come with the [React Snippets Extension](https://marketplace.visualstudio.com/items?itemName=runningcoder.react-snippets)

Install the React Snippets Extension with `ext install runningcoder.react-snippets`

Bonus:
======

Here are a few other settings and extensions I use to boost my workflow:

1.  [**Vim**](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim) — I don’t currently use this extension myself because I’m not as skilled in Vim as I wish I was but the shortcuts in Vim are useful enough to include.
2.  [**Windows Default Keybindings**](https://marketplace.visualstudio.com/items?itemName=smcpeak.default-keys-windows) — Maybe more experienced Linux users know if there’s a good reason for this but the keyboard shortcuts on Linux use more keys than on Windows/Mac. I just switched to Linux full time and was accustomed to VSCode on Windows so this made the transition easier.
3.  [**Shortcuts**](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf) — Not an extension but VSCode has a ton of useful keyboard shortcuts that are super useful. The full list is linked but here are a few that I use the most:

######**Viewer shortcuts:**

Ctrl-\` — toggles the terminal

Ctrl-B — toggles the side panel.

Ctrl-Shift-P — Show command palette.

######**Code navigation:**

Ctrl-Shift-o — Go to symbol. This lets you search your functions and variables which makes going to and from functions in a file much quicker.

Ctrl-Alt-Up/Down — Copy your line up or down.

Ctrl-X — Works with a selection but if your cursor is just sitting on a line it will cut the whole line without selection. Same with Ctrl-C

Ctrl-Enter — Enters a line below. I use this one all the time because it allows you to insert a line without being at the end of the line.

Ctrl-/ — Not specific to VSCode but one you should know for adding/removing line comments.

######**Directory Navigation:**

Ctrl-P — opens a search for files in your project to be opened

Ctrl-tab / Ctrl-Shift-tab — same as in Chrome this moves you backward or forwards to the files you have viewed.

Ctrl-W — Again same as Chrome, this closes your current file window.

Ctrl-Shift-L — searches the whole project instead of just the file that's open

*Thanks for reading! Let me know your favorite code extension and keyboard shortcuts*
