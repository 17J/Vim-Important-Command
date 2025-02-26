## Vim Editor command important

# Navigation

- `gg`: Go to the first line.
- `G`: Go to the last line.
- `:nu + Enter`: Go to a specific line number (e.g., :25 + Enter).
- `Ctrl + w w`: Switch between windows (useful in split-screen mode).
- `/word`: Search forward for "word".
- `?word`: Search backward for "word".
- 
# Editing

- `i`: Insert text before the cursor.
- `a`: Append text after the cursor.
- `o`: Open a new line below the current line and insert text.
- `Shift + o`: Open a new line above the current line and insert text.
- `Shift + i`: Insert at the beginning of the current line.
- `Shift + a`: Append at the end of the current line.
- `x`: Delete the character under the cursor.
- `dd`: Delete the current line.
- `r`: Replace the character under the cursor.
- `:%s/word1/word2/g`: Replace all occurrences of "word1" with "word2" in the file.
- `Ctrl + r`: Redo the last undone change.
- `u`: undo last change.
- `:e!`: Revert all changes since the last save.
# Copying and Paste

- `v` : Visual mode (character-wise selection).
- `Shift + v `: Visual line mode (line-wise selection).
- `y` : Yank (copy) the selected text.
- `p`: Paste after the cursor.
- `Shift + p`: Paste before the cursor.
- 
# File Management
- `:w` : Save the file.
- `:q` : Quit Vim.
- `:wq` or `:x` : Save and quit.
- `:qa` : Quit all open buffers.
- 
# Diffing

- `vimdiff file1.txt file2.txt`: Open files in diff mode (side-by-side).
- `vimdiff -o file1.txt file2.txt`: Open files in diff mode (horizontal split).
- `:diffget`: Get changes from the other diff window.
- `:diffput`: Put changes to the other diff window.
- `:diffupdate`: Update diff information.
- `:set scrollbind`: Enable synchronized scrolling in diff mode.
- `:set noscrollbind`: Disable synchronized scrolling in diff mode.
- 
# Appearance

- `:set nu`: Enable line numbers.
- `:set nonu`: Disable line numbers.
- `:syntax on`: Enable syntax highlighting.
- `:syntax off`: Disable syntax highlighting.

