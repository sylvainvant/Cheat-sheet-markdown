# Vim

### Cursor movement

* h = move cursor left
* j = move cursor down
* k = move cursor up
* l = move cursor right
* H = move to top of screen
* M = move to middle of screen
* L = move to bottom of screen
* w = jump forwards to the start of a word
* W = jump forwards to the start of a word (words can contain punctuation)
* e = jump forwards to the end of a word
* E = jump forwards to the end of a word (words can contain punctuation)
* b = jump backwards to the start of a word
* B = jump backwards to the start of a word (words can contain punctuation)
* % = move to matching character (default supported pairs: '()', '{}', '[]' - use :h matchpairs in vim for more info)
* 0 = jump to the start of the line
* ^ = jump to the first non=blank character of the line
* $ = jump to the end of the line
* g*_* = jump to the last non=blank character of the line
* gg = go to the first line of the document
* G = go to the last line of the document
* 5G = go to line 5
* fx = jump to next occurrence of character x
* tx = jump to before next occurrence of character x
* Fx = jump to previous occurence of character x
* Tx = jump to after previous occurence of character x
* ; = repeat previous f, t, F or T movement
* , = repeat previous f, t, F or T movement, backwards
* } = jump to next paragraph (or function/block, when editing code)
* { = jump to previous paragraph (or function/block, when editing code)
* zz = center cursor on screen
* Ctrl + e = move screen down one line (without moving cursor)
* Ctrl + y = move screen up one line (without moving cursor)
* Ctrl + b = move back one full screen
* Ctrl + f = move forward one full screen
* Ctrl + d = move forward 1/2 a screen
* Ctrl + u = move back 1/2 a screen

### Cut and past

* (0)dd = delete (0) line.s
* (0)d(j)(k) = delete (0) line.s (at the bottom with j and at the top with k) 
* D = delete from the cursor to the end of the line
* (0)dw = delete (0) word.s from the cursor to the end of the word
* (0)diw = delete (0) whole word.s 
* (0)x = delete character
* (0)yy / (0)Y = yank (0) a line.s
* (0)yw = yank (0) word.s
* y$ = yank to end of line
* p = paste after cursor
* P = paste before cursor


### Editing 

* (0)r = replace (0) character.s
* (g)J = join line below to te current one wit one space(g with no space) in between
* cc = replace entire line
* c$ = replace to the end of the line
* ciw = replace entire word
* cw = replace to the end of the word
* s = delete character and substitute text
* S = delete line and substitute text (same as cc)
* xp = transpose two letters (delete and paste)
* u = undo
* Ctrl + r = redo
* . = repeat last command

### Insert mode - inserting/appending text

* i = insert before the cursor
* I = insert at the beginning of the line
* a = insert after the cursor
* A = insert at the end of the line
* o = append a new line below the current line
* O = append a new line above the current line
* ea = insert at the end of the word
* Esc = exit insert mode

### Exiting

* w = write (save) the file, but don't exit
* w !sudo tee % = write out the current file using sudo
* wq or :x or ZZ = write (save) and quit
* q = quit (fails if there are unsaved changes)
* q! or ZQ = quit and throw away unsaved changes
* wqa = write (save) and quit on all tabs

