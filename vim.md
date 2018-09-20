# notes on vim course

`gg` goto the beginning of the file

`G` goto the end of the file

`$` got the end of the line

`u`  undo

`ctrl-r` redo

`r` replace from that position onwards

`cit` clear everything within this tag

`cw` clear word

`ci{` clear everything within the {!!!

`vwwwwww` in a block of text select multiple words with

`y` copy that selection

`y$` yank from cursor to the end of the line!

`yy` yank to whole line

`y10` yank 10 lines

`p` paste that selection

`v` open Visual mode on position

`vw` select a single word from cursor

`shift-v` / `V` open visual mode selecting entire line

`ctrl-v` op visual block mode

`"+P` paste system clipboard, alternatively by `:set paste`

`d$` delete everything from the cursor to the end of the line

`d^` or `d0` delete everything from the cursor to the start of the line

`dw` delete next word

`dG` delete until the end

`:g/#/d` delete all lines starting with the pattern `#`!

`ggVG` select all

`fCHARACTER` find on this line the next CHARACTER

`>>` indent to the right

`<<` indent to the left

`! rspec` excecute rspec on current path and return to current window

## managing views / windows

`sp` split horizontally
`vsp` split vertically (`:set splitright` to override the default split left)
`ctrl ww` cycles though openend panes
