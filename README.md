# Surround.vim is a plugin for surrounding words on Vim

### if you haven't installed it yet, come here : https://vimawesome.com/plugin/surround-vim


## Add surrounding

With this plugin you can surround words or sentences with a simple command in vim

For example we have a sentence : `Hello world` 

If i want to surround it with ***double quotation*** marks, i start by placing my cursor on the word and i will use the `yss"` command

`yss" = "Hello world"`

And i can also use the command to add ***brackets, parenthesis*** and ***many others***, using *yss* and then the symbols with which i want to surround my sentences

`yss] = [Hello world]`

`yss) = (Hello world)`

*Tips* for ***(parenthesis),[brackets]*** and ***{braces}*** if we use the characters that open these signs we will have an extra space between the word and its surroundings, example : 

### ***With space***

`yss( = ( Hello world )`  
`yss[ = [ Hello world ]`

### ***Without space***

`yss) = (Hello world)`    
`yss] = [Hello world]`

Now you can surround an entire sentence with the desired character, but you can't surround just one or two words

If you want to surround ***only*** one word you can use `ysw)` to surround the word with *parenthesis* ***from the cursor to the end of the word***, some examples :

#### * = my cursor

`ysw) = H*(ello) world`  
`ysw) = Hello *(world)`   
`ysw) = *(Hello) world`  

If i want to surround the complete word then i use `ysiw` ( is = entire word) with this command even if my cursor is in the center of the word, ***the whole word*** will be surrounded

`ysiw' = 'He*llo' world`  
`ysiw- = Hello -wo*rld-`  

I can also surround many words ***by replacing*** the "***x***" in this command `ysXaw` with a ***number***

`ys2aw) = (*Hello at) world`  
`ys2aw} = Hello *{at world}`  
`ys3aw[ = [ He*llo at world ]`  

And if I want to surround my words with HTML tags it's possible, they will even close themselves, for example:  

`ysiw<p> = <p>Hello world</p>`  
`ys2aw<h1> = <h1>Hello world</h1>`   

Let's finish by doing a v ( to put it in visual mode on vim) then selecting all the lines we want to surround followed by an S and the desired entourage, example:  

`v S<p> = <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis augue metus</p>`  

It also allows you to surround a block of text even with spaced lines

```
v S<em> = <em>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis augue metus, 
pellentesque non volutpat vitae, consequat ut purus

Vivamus quis dui sodales lacus hendrerit volutpat.
Phasellus ac sagittis arcu.</em>
```

And to include a text in a tag

```
VS<em> = <em>
         Hello world
         </em>
```

---

## Replace surrounding


