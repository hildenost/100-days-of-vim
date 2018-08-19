# Log

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
