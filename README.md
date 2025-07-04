# vscode_bindings

## Normal Mode

| Command         | Description                              |
|-----------------|------------------------------------------|
| `<Shift>+h`     | Move to the previous buffer               |
| `<Shift>+l`     | Move to the next buffer                   |
| `<leader>v`     | Open vertical split window                |
| `<leader>s`     | Open horizontal split window              |
| `<leader>h`     | Move to the pane on the left              |
| `<leader>j`     | Move to the pane below                    |
| `<leader>k`     | Move to the pane above                    |
| `<leader>l`     | Move to the pane on the right             |
| `<leader>w`     | Save file (Force Save)                    |
| `<leader>q`     | Close file (Force Quit)                   |
| `<leader>x`     | Save and quit file (Force Save and Quit)  |
| `[d`            | Jump to the previous error or warning     |
| `]d`            | Jump to the next error or warning         |
| `<leader>ca`    | Open Quick Fix                            |
| `<leader>f`     | Quick Open (Search files)                 |
| `<leader>p`     | Format document                           |
| `gh`            | Show definition preview hover             |

## Visual Mode

| Command         | Description                              |
|-----------------|------------------------------------------|
| `<`             | Outdent (Decrease indentation)           |
| `>`             | Indent (Increase indentation)            |
| `J`             | Move line down                           |
| `K`             | Move line up                             |
| `<leader>c`     | Toggle comment for the selection         |

---

# Key Bindings Table

## Navigation

| Command               | Description                                         | Condition                    |
|----------------------|-------------------------------------------------|-----------------------------|
| `Ctrl+Shift+A`        | Focus on the next terminal                        | When terminal is focused     |
| `Ctrl+Shift+B`        | Focus on the previous terminal                    | When terminal is focused     |
| `Ctrl+Shift+J`        | Toggle panel                                      | -                           |
| `Ctrl+Shift+N`        | Open a new terminal                               | When terminal is focused     |
| `Ctrl+Shift+W`        | Close the current terminal                        | When terminal is focused     |

## File Tree

| Command               | Description                                         | Condition                    |
|----------------------|-------------------------------------------------|-----------------------------|
| `Ctrl+E`             | Toggle sidebar                                     | -                           |
| `Ctrl+E`             | Focus on file explorer                             | When focused in editor       |
| `N`                  | Create new file                                    | When focused in Files Explorer and no input field is active |
| `R`                  | Rename file                                        | When focused in Files Explorer and no input field is active |
| `Shift+N`            | Create new folder                                  | When focused in Explorer viewlet |
| `Shift+N`            | Open new window                                    | When not focused in Explorer viewlet |
| `D`                  | Delete file                                        | When focused in Files Explorer and no input field is active |

---

# Typing and Inserting Text

| Command   | Description                                                       |
|----------|------------------------------------------------------------------|
| `i`      | Enter Insert mode to start typing from the current position       |
| `I`      | Enter Insert mode at the beginning of the line                    |
| `a`      | Enter Insert mode after the current position                      |
| `A`      | Enter Insert mode at the end of the line                          |
| `o`      | Insert a new line below and enter Insert mode                     |
| `O`      | Insert a new line above and enter Insert mode                     |
| `Esc`    | Exit Insert mode and return to Normal mode                        |

---

# Selecting and Editing Text

| Command     | Description                                                         |
|------------|--------------------------------------------------------------------|
| `v`        | Enter Visual mode to select text character by character            |
| `V`        | Enter Visual Line mode to select entire lines                      |
| `Ctrl+v`   | Enter Visual Block mode to select a block of text                  |
| `y`        | Yank (copy) the selected text                                      |
| `p`        | Paste the yanked text                                              |
| `u`        | Undo the last action                                               |
| `Ctrl+r`   | Redo the previously undone action                                  |

---

# Deleting Text

| Command      | Description                                                          |
|-------------|--------------------------------------------------------------------|
| `x`         | Delete the character under the cursor                              |
| `dd`        | Delete the entire line                                             |
| `d{motion}` | Delete text based on motion, e.g., `dw` (delete next word), `d$` (delete to the end of the line) |
| `D`         | Delete from the current position to the end of the line             |
| `c{motion}` | Delete and immediately enter Insert mode, e.g., `cw` (delete next word and start typing new text) |
| `r`         | Replace the current character with the specified one               |

---

# Editing and Modifying Text

| Command   | Description                                                          |
|----------|---------------------------------------------------------------------|
| `R`      | Enter Replace mode to overwrite text                                 |
| `s`      | Delete the character under the cursor and enter Insert mode          |
| `S`      | Delete the current line and enter Insert mode                        |
| `J`      | Join the current line with the next one                              |
| `~`      | Toggle the case of the character under the cursor (upper/lower case)  |
