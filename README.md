# vim-practise


### 17-Sep-2015 

##### NERDTree
Keyboard Commands
- t: Open the selected file in a new tab
- i: Open the selected file in a horizontal split window
- s: Open the selected file in a vertical split window
- I: Toggle hidden files
- m: Show the NERD Tree menu
- R: Refresh the tree, useful if files change outside of Vim
- ?: Toggle NERD Tree's quick help

Switch between tabs
- gt = next tab
- gT = previous tab

Switch between main Editor and NERDTree window
- ctrl+ww cycle though all open windows

##### Column Edit
To edit a column, follow these steps:
- Stand on the beginning of the column
- Press Ctrl+Shift+v, then mark across the column you want to edit.
- Press Shift+i to insert text at the beginning of the column, Shift+a to append text, r to replace highlighted text, d to delete, c to change... etc.
- Hit ESC when done.


### 16-Sep-2015 Basics 
#### This tutorial is based on [openvim](http://www.openvim.com/tutorial.html)
- Two modes, insert (i) and normal (esc)
- Basic movement: h, j, k, and l
- Word movement: w, e, b
- Number powered movement, e.g. 5(w|b|e|l)
- Insert text repeatedly, e.g. 3iYes + esc
- Find a character, f and F e.g. fg, 3fg, Fg
- Go to matching parentheses, %
- Go to start/end of line, 0 and $
- Find word under cursor, * and #
- Goto line, g and G eg. gg, G, 10G
- Search, /text with n and N
- Insert new line, o and O
- Removing a character, x and X
- Replacing letter under cursor, r
- Deleting, d eg. dw, d2w, d2e
- Repetition with .
- Visual mode, v

