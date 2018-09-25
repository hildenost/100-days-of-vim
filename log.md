# Log

## Day umpteenth: Tuesday September 25 2018
I don't really do log editing, it seems.
Meanwhile I have been finishing my PhD thesis, editing it in `vim` of course.
So, technically, I *have* been doing at least 1 hour of `vim` every day, it's just that nobody knows.

I've learnt a large bunch of new skills since then!
I am safe to say that I will use `vim` from now on as my preferred editor.
I will need to find a proper way to set up `python` and `C++`, but I'm sure the internet will help me.

On that note, I've started a mini project.
I aim to create some mini bridge example games in `JavaScript`.
Progress came to a halt when I tried to install `prettier` to make everything pretty, and accidentally wiped out my game source file.
Ah, no worries, you might say, you are using `git`!

...

Well.

...

I didn't use `git` --- yet.
You know, since I was just familiarising myself with `JavaScript` and the game engine.
Nothing serious.
I can start a repo later.

So, I've since created the repo.
It's called [browser-bridge](../browser-bridge/).

Anyway, what I did tonight was that I set up my `.vimrc` file!
I've set it up for `JavaScript` development in mind.
For now.


## Day 3: Sunday August 19 2018

* Minor editing of this log file

### Key bindings used
* `cw` to rewrite word


## Day 2: Friday August 17 2018

* Used vim as LaTeX editor almost entire work day

### Key bindings used
* `<F6>` was remapped to compiling

* `e` - `E` jump forwards to end of word without/with punctuation
* `w` - `W` jump forwards to start of word without/with punctuation
* `b` - `B` jump backwards to start of word without/with punctuation

* `0` move to beginning of line

Using the move commands with punctuation was really handy when dealing with
LaTeX commands and editing equations.

* `/search/replace/gc` with the option flag `c` to verify every search result before replacing
* `v` and selecting with `hjkl` keys, then `:s` before the above phrase, to select a limited part
of the document

### What hindered me?
Normally, I edit LaTeX files in Visual Studio Code with the LaTeX Workshop extension.
This extension lists all my labels and citation labels so I don't have to remember them or try to find the
equation label manually.
I will check out possible vim extensions to solve this problem.

## Day 1: Thursday August 16 2018

* Added `set number` to my `.vimrc` file
* Edited Readme.md and log.md using vim
* Installed hugo, wrote an *About* page in vim, and failed deploying it

### Key bindings used
* `h`-`j`-`k`-`l` left - down - up - right keys for moving the cursor

* `r`- `R` replacing 1 or more characters

* `x` deleting character under cursor

* `o` - `a` **o**pen new line or **a**ppend

### What hindered me?
I replaced some longish text with some shorter text. I want to delete from that spot until end of line.
