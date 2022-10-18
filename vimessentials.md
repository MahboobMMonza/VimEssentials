# VI Essentials

## Different Modes:
You will see the current mode in the bottom left of the editor. If you don't see a mode, you are in **NORMAL** mode.

**NORMAL** Mode - You can move around and use commands

**INSERT** Mode - You can type stuff

**VISUAL** Mode - You can select stuff

**COMMAND** Mode - Type commands

In **NORMAL** mode, type `v` to enter **VISUAL** mode.

In NORMAL mode, type `i` to enter **INSERT** mode.

In NORMAL mode, type `:` to enter **COMMAND** mode.

Press `esc` to enter **NORMAL** mode.


## Basic Movement:

`h` move backward one character 

`j` move down one character 

`k` move up one character 

`l` move forward one character 

`w` move forward one word

`b` move backward one word 

`gg` move to top of file

`G` move to bottom of file

`{` move up one paragraph

`}` move up one paragraph

`$` move to end of line

`0` move to beginning of line

## Basic Useful Commands (in **NORMAL** mode):

`:q` quit

`:wq` save (write) and quit

`:q!` quit without saving

`ZZ` save and quit


`i` enter **INSERT** mode before cursor

`I` enter **INSERT** mode at beginning of line

`a` enter **INSERT** mode after cursor

`A` enter **INSERT** mode at end of line

`o` enter **INSERT** mode in a new line underneath the cursor

`O` enter **INSERT** mode in a new line above the cursor.

There are more ways to enter insert mode (look into c, s)


`u` undo the last command

`<ctrl>+r` redo the last command

`.` repeat the previous command


`dd` cut (delete) the current line

`yy` copy (yank) the current line

`p` paste the previous selection after cursor

`P` paste the previous selection before cursor


`/foo` search for "foo" in the file

`n` go to the next search match

`N` go to the previous search match

`*` search for the word under the cursor 
