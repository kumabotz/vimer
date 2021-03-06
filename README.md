# vimer

Take this and slash the dragon
https://github.com/kumabotz/dotfiles/blob/master/vim

## Theme
- Follow setup for `agnoster` theme from https://github.com/robbyrussell/oh-my-zsh/wiki/Themes
- Install fonts from https://github.com/Lokaltog/powerline-fonts/blob/master/Inconsolata/Inconsolata%20for%20Powerline.otf

## TIPS
- `f` find in line
- `F` find backward in line
- `vt<CHAR>` select until character
- `vi<CHAR>` select inside character
- `va<CHAR>` select around character (character is included)
- `gc` comment line
- `gcgc` uncomment line
- `m<CHAR>` mark current line
- `<backtick><CHAR>` go to mark
- `C-w<hjkl>` navigate window inside vim
- `ACK` https://github.com/mileszs/ack.vim#keyboard-shortcuts
- `C-o` prev buffer
- `C-i` next buffer
- `C-t` open in new tab
- recover closed tab
  1. `:ls` to get the buffer number
  1. `:tabnew +Nbuf` or `:bN` at new tab where N is the buffer number
- `C-p C-b` show recent files
- `C-x` open file in horizontal window
- `C-v` open file in vertical window
- `S-v <num>G` select until line <num>
- `%` go to match closing / opening tag
- `;`, `,` repeat the last `f` or `F`
- `S` clear current line; to insert mode
- `>>` `<<` indent and unindent in normal mode
- `:Gblame` git blame
- `q<CHAR>` start recording macro binding to `<CHAR>`, stop recording with `q`, `@<CHAR>` to apply macro
- `gd` go to definition
- `[{` jump back to `{`
- `cw` change the word
- `D` delete till the end of line
- folding for js and scss `set foldmethod=marker` `set foldmarker={,}`
- `:tabdo e` reload all tabs
- `retab` format tab / indentation with current tab settings

## TODO
- enable insert after quote (current: `jk, a`)

## References
- https://github.com/aranair/dotfiles
- https://github.com/yeouchien/cbvim
- https://github.com/allenlsy/.vim
