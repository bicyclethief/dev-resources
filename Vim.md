
# Useful Vim Tricks

+ `gi` switches to insertion mode placing the cursor at the same location it was previously
+ `g;` go back to the last location you edited (can be done multiple times going
  back into history)
+ `*` will search for the word under the cursor
+ [EasyMotion](https://github.com/Lokaltog/vim-easymotion): `<leader><leader>s`
+ `f <char>` scan line for next occurrence of character
  + `;` move to next occurrence
  + `,` move to previous occurrence
+ marks:
  + `m <key>` sets mark
  + `' <key>` returns cursor to mark
+ window splits:
  + `:split <filename>` split horizontal
  + `:vsplit <filename>` split vertical
  + `:only` close all windows except current one
  + `<c-w> [h|j|k|l]` move focus to window according to direction
+ tabs:
  + `:tabn <filename>` open a file in a new tab 
  + `gt` move to the next tab
  + `gT` move to the previous tab
  + `#gt` move to tab number #
  + `tabmove #` move current tab to the #th position (indexed from 0)
  + `tabo` close all tabs except for current one
+ searching and opening files as a tab:
  + `<c-p>` invoke [CtrlP](https://github.com/kien/ctrlp.vim)
  + type in fuzzy file search
  + `<c-t>` to open as tab
  + `<c-v>` to open in vertically split window
  + `<c-x>` to open in horizontally split window
+ scrolling:
  + `H` jump to the high part of the screen
  + `M` jump to the middle part of the screen
  + `L` jump to the low part of the screen
  + `zt` scroll so the current line is at the top
  + `zz` scroll so the current line is in the middle
  + `zb` scroll so the current line is at the bottom
