
# Text Editors

## General

- SPC f s : Save file
- SPC f t : Open file tree (Neo-tree)
- SPC f o : Open Oil file browser (toggle)
- SPC f f : Format file (normal mode) / Format region (visual mode)
- SPC o t : Open terminal
- SPC o f : Open file (same as search files)
- SPC o u : Open undo tree
- Ctrl + Shift + F : Search whole project for string

## Windows

- SPC w / : Window split vertically
- SPC w - : Window split horizontally
- SPC w c : Close window
- SPC w w : Switch windows
- SPC w l : Move to right window
- SPC w h : Move to left window
- SPC w j : Move to lower window
- SPC w k : Move to upper window
- SPC w L : Move window to right
- SPC w H : Move window to left
- SPC w J : Move window to lower
- SPC w K : Move window to upper

## Buffers

- SPC b b : Open buffer search (workspace)
- SPC b B : Open all buffer search
- SPC , : Open buffer search (workspace)
- SPC Shift + , : Open all buffer search
- SPC b c : Close buffer
- SPC b s : Scratch buffer
- SPC b u : Reopen last buffer
- SPC b l : Move buffer to right window
- SPC b h : Move buffer to left window
- SPC b j : Move buffer to lower window
- SPC b k : Move buffer to upper window

## Text Manipulation

- Alt + Up/k : Move line up
- Alt + Down/j : Move line down
- Ctrl + Alt + Up/k : Multicursor add line up
- Ctrl + Alt + Down/j : Multicursor add line down
- i/I (visual mode) : Add cursors to visual selection

## LSP

- SPC ; : Comment out line(s)
- SPC c c : Compile
- SPC c d : Jump to definition
- SPC c D : See references
- SPC c k : Jump to documentation
- SPC c r : Rename all references
- SPC c s : Send to repl
- SPC c x : LSP diagnostics
- SPC c t : Find type definition
- SPC c o : Organize imports
- SPC c w : Remove trailing whitespace
- SPC c W : Remove trailing newlines
- SPC c e : Next error
- SPC c E : Previous error

## Errors

- SPC e e : Show errors (Trouble)
- SPC e f : Fix error
- SPC e l : List errors
- SPC e n : Next Error
- SPC e N : Previous error
- SPC e p : Previous error

## Jump

- SPC j c : Jump to previous change
- SPC j C : Jump to next change
- SPC j l : Jump to line
- SPC j w : Jump to word (Flash)
- SPC j t : Jump to treesitter node (Flash)
- SPC j r : Remote flash (operator mode)
- SPC j R : Treesitter search (visual/operator mode)

## Git

- SPC g g : Open magit/neogit

## Toggle

- SPC t n : Toggle neck saver (center mode)
- SPC t c : Toggle center mode (same as above)
- SPC t + : Toggle width increase
- SPC t - : Toggle width decrease
- SPC t p : Toggle precognition (movement hints)

## Command/Search

- SPC SPC : Command palette (Telescope commands)

## Moved/Relocated Keybinds

- SPC d e : Show diagnostic error messages (moved from SPC e)
- SPC d b : Debug toggle breakpoint (moved from SPC b)
- SPC d B : Debug set breakpoint with condition
- SPC l a : LSP code action (moved from SPC c a)
- SPC l r : LSP rename (moved from SPC r n)

# Window Managers

## General

- Mod + Shift + C : Kill program

## Program Launcher (Rofi/Wofi)

- Mod + Space

## Layout changes

- Mod + , : Previous layout
- Mod + . : Next layout