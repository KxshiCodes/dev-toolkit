# Basic nvim Commands 

## Typicl Workflow

```bash
`nvim`              # Enter Neovim from terminal.
`nvim {filename}.rb`# Enter a folder in Neovim.

     `k`            # Move the cursor up.
 `h`     `l`        # Move the cursor left and right
     `j`            # Move the cursor down.

`i`                 # Enters Insert mode from Normal mode.
`v`                 # Enter visual mode.
`d{motion}`         # Delete the text that is moved over with the specified motion (e.g., dw will delete the current word).
`dd`                # Delete the current line.
`u`                 # Undo the last change.
`Ctrl + r`          # Redo the last undone change.
`:w`                # Save the current file.
`:w {file}`         # Save the current file as the specified file.
`:wq`               # Save and quit.
`:q`                # Quit.
`:q!`               # Quit without saving.
`Esc`               # Exit insert mode.

```


## Navigation

```bash
     `k`            # Move the cursor up.
 `h`     `l`        # Move the cursor left and right
     `j`            # Move the cursor down.

     `{`            # Move the cursor to the beginning of the current word.
 `b`     `w`        # Move the cursor to the beginning of the next word.
     `}`            # Move the cursor to the bottom of the current paragraph.

`e`                 # Move the cursor to the end of the current word.
`gg`                # Move the cursor to the beginning of the file.
`G`                 # Move the cursor to the end of the file.
`{number}G`         # Move the cursor to the specified line number.
`:{line number}`    # Move the cursor to the specified line number.
```

## Editing

```bash
`i`                 # Enter insert mode at the current cursor position.
`I`                 # Enter insert mode at the beginning of the current line.
`a`                 # Enter insert mode after the current cursor position.
`A`                 # Enter insert mode at the end of the current line.
`o`                 # Insert a new line below the current line and enter insert mode.
`O`                 # Insert a new line above the current line and enter insert mode.
`r`                 # Replace the character under the cursor.
`R`                 # Enter replace mode.
`x`                 # Delete the character under the cursor.
`X`                 # Delete the character before the cursor.
`d{motion}`         # Delete the text that is moved over with the specified motion (e.g., dw will delete the current word).
`dd`                # Delete the current line.
`{Visual mode}`     # Select text to operate on it (e.g., d will delete the selected text).
```

## Copy, Paste, Delete in Visual Mode

```bash
`v`                 # Enter visual mode.
`V`                 # Enters Visual line mode from Normal mode.
`y`                 # Yank mode copies selection.
`y`                 # Delete copies and deletes the selection.
`p`                 # Paste the text that was last yanked or deleted after the cursor.
`P`                 # Paste the text that was last yanked or deleted before the cursor.
`yy`                # Copy the current line.
```

## Search & Find

```bash
`/`                 #  Initiates a search.
`n`                 # Jump to the next match of the current search pattern.
`N`                 # Jump to the previous match of the current search pattern.
```

## File management

```bash
`:e {file}`         # Open the specified file.
`:ls`               # List all open buffers.
`:b {buffer number}`# Switch to the specified buffer.
`:bd`               # Close the current buffer.
```

## Syntax highlighting

```bash
`:syntax on`        # Enable syntax highlighting.
`:syntax off`       # Disable syntax highlighting.
```

## Indentation

```bash
`>`                 # Indent the current line.
`<`                 # Unindent the current line.
`==`                # Auto-indent the current line.
`=%`                # Auto-indent the current block (e.g., a function).
```

## Help

```bash
`:help {topic}`     # Display the help for the specified topic.
`:help user-manual` # Open the Neovim user manual in a browser.
```
