# vim cheat sheet

[VIM Cheatsheet](https://devhints.io/vim)

## Commands more useful

* Close file- !q
* Save and close file- :wq

* Exit Insert Mode- Esc
* Insert Mode - i

* Remove everything from cursor to end of file - dG
* copy line - yy
* paste below - p
* delete line - dd
* undo changes - u

* copy/pasting a section
  1. Position the cursor where you want to begin cutting.
  2. Press v to select characters (or uppercase V to select whole lines).
  3. Move the cursor to the end of what you want to cut.
  4. Press d to cut (or y to copy).
  5. Move to where you would like to paste.
  6. Press P to paste before the cursor, or p to paste after.

* first line - gg
* last line - G
* start of line - ^
* end of line - $
* next line with insert mode - o
* go to line n - :n
* go to word pod - /pod and then n

## bash commands

* To search command history in bash type 'Ctrl + r' 
 This will open reverse search prompt. You can type in search word and it will show commands
 If press enter and command will execute
 If press right or left arrow you can edit the command

* Ctrl + a => Return to the start of the command you’re typing
* Ctrl + e => Go to the end of the command you’re typing
* Ctrl + w => Delete the word / argument left of the cursor
* Ctrl + l => Clear the screen
