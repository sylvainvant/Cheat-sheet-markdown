# Vim

### Cut and past

* (0)dd = delete (0) line(s)
* (0)d(j)(k) = delete (0) line(s) (at the bottom with j and at the top with k) 
* D = delete from the cursor to the end of the line
* (0)dw = delete (0) word(s) from the cursor to the end of the word
* (0)diw = delete (0) whole word(s) 
* (0)x = delete character
* (0)yy / (0)Y = yank (0) a line(s)
* (0)yw = yank (0) word(s)
* y$ = yank to end of line
* p = paste after cursor
* P = paste before cursor


### Editing 

* (0)r = replace (0) character
* (g)J = join line below to te current one wit one space(g with no space) in between
* cc = (replace) entire line
* c$ = (replace) to the end of the line
* ciw = (replace) entire word
* cw = (replace) to the end of the word
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

