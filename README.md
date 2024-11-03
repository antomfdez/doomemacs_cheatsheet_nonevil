# Doom Emacs Cheatsheet: Non-Evil Mode

**Note:** This cheatsheet is tailored for Doom Emacs in non-Evil mode. If you're using Evil, the keybindings will differ significantly.

## Basic Navigation

### Cursor Movement
- `C-p`: Move cursor up one line
- `C-n`: Move cursor down one line
- `C-f`: Move cursor forward one character
- `C-b`: Move cursor backward one character
- `C-a`: Move cursor to start of line
- `C-e`: Move cursor to end of line
- `M-b`: Move cursor back one word
- `M-f`: Move cursor forward one word

## Editing

### Undo/Redo
- `C-/`: Undo last change
- `C-x u`: Redo last change

### Deleting
- `C-d`: Delete character under cursor
- `M-d`: Delete word under cursor
- `C-k`: Kill (delete) text from cursor to end of line
- `C-w`: Kill (delete) region

### Searching and Replacing
- `C-s`: Search forward
- `C-r`: Search backward
- `M-%`: Replace text
- `C-M-s`: Regex search

## Buffers and Windows

### Managing Buffers
- `C-x C-b`: List buffers (d - select for kill/ x - kill the selected)
- `C-x b`: Switch to a buffer
- `C-x k`: Kill (close) a buffer
- `C-x C-c`: Save current buffer

### Window Management
- `C-x 2`: Split window horizontally
- `C-x 3`: Split window vertically
- `C-x 0`: Delete current window
- `C-x 1`: Keep only the current window
- `C-x o`: Switch to other window

### Resize
- `C-u 10 <shortcut>`: Repeat the `<shortcut>` 10 times
- `C-x }`: Resize 1px (increase width)
- `C-x {`: Resize 1px (decrease width)

## Files and Directories

- `C-x C-f`: Find files

### Dired
- `C-x d`: Open dired in minibuffer
- `RET`: Open actual dir in current buffer (type non-existent name to create new)

#### In Dired Buffer
- `^`: One dir back
- `+`: Create dir
- `g`: Refresh dired
- `RET`: Enter dir

## Execute Function

### Keys
- `M-x`: Execute functions

### Layouts
- `persp-load-state-from-file`: Load layout and buffers from a file
- `persp-save-state-to-file`: Save current layout and buffers to a file
