# Text Editor cheatsheet

## Vim 

### Basic Commands
| command | description                                           | 
| ------- | ----------------------------------------------------- |
|  i      | insert text at cursor                                 |
|  :w     | save current file                                     | 
|  :q     | quit (save prompt if file is modified)                |
|  :q!    | force quit without saving                             |
|  :wq    | save and quit                                         |
|   y     |  copy current line                                    |
|   p     |  paste what has been yanked                           |


### Advanced Commands 
| command | description | 
| --------|------------- |
| r{char} | replace the character under the cursor with {char}.   |
| /{pattern}/| search for {pattern}                               |


## Emacs
- C = left ctrl


### Saving

| command | description                                               | 
| --------|---------------------------------------------------------- |
| C-x C-s | save current file to associated filename                  | 
| C-x C-w | save current file to new filename                         |



### Moving the Cursor
| command | description                                               | 
| --------|---------------------------------------------------------- |
| C-a     | move cursor to the beggining of the line                  | 
| C-e     | move cursor to the beginning of the line                  |
| C-f     | move cursor forward one character                         |
| C-b     | move cursor baack one character                           |
| Esc f   | move cursor forward one word                              |
| Esc b   | move cursor backward one word                             |
| C-n     | move cursor down one line                                 |
| C-p     | move cursor up one line


## Nano 

### Basic commands

| command | description  | 
| --------|------------- |
| ctrl-O  | Save current file | 
| ctrl-X  | Exit nano    |