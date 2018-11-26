# Surround.vim is a plugin for surrounding words on Vim

### if you haven't installed it yet, come here : https://vimawesome.com/plugin/surround-vim

With this plugin you can surround words or sentences with a simple command in vim

for example we have a sentence : `Hello world` 

if i want to surround it with ***double quotation*** marks, i start by placing my cursor on the word and i will use the `yss"` command

`yss" = "Hello world"`

And i can also use the command to add ***brackets, parenthesis*** and ***many others***, using *yss* and then the symbols with which i want to surround my sentences

`yss] = [Hello world]`

`yss) = (Hello world)`

*Tips* for ***(parenthesis),[brackets]*** and ***{braces}*** if we use the characters that open these signs we will have an extra space between the word and its surroundings

### ***Example*** : 

### ***With space***

`yss( = ( Hello world )`  
`yss[ = [ Hello world ]`

### ***Without space***

`yss) = (Hello world)`    
`yss] = [Hello world]`

Now you can surround an entire sentence with the desired character, but you can't surround just one or two words

if you want to surround ***only*** one word you can use `ysw)` to surround the word with *parenthesis* ***from the cursor to the end of the word, some examples*** :
