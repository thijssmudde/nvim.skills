# NVIM

⏺ Here are some powerful Neovim productivity techniques you might not know:

  Advanced Navigation & Motions

  Jump to specific characters:
  - f{char} / F{char} - Jump forward/backward to character
  - t{char} / T{char} - Jump to before/after character
  - ; / , - Repeat last f/t motion forward/backward

  Word boundaries:
  - W / B - Jump by WORD (space-separated) instead of word
  - ge / gE - Jump to end of previous word/WORD

  Line-specific:
  - 0 / ^ / $ - Start of line / first non-blank / end of line
  - g_ - Last non-blank character of line
  - {number}| - Jump to specific column

  Text Objects (Game Changer!)

  Around vs Inside:
  - ciw - Change inside word
  - caw - Change around word (includes spaces)
  - ci" / ca" - Change inside/around quotes
  - ci) / ca) - Change inside/around parentheses
  - cit / cat - Change inside/around HTML/XML tags

  Advanced text objects:
  - cip / cap - Change inside/around paragraph
  - ci} / ca} - Change inside/around braces
  - ci] / ca] - Change inside/around brackets

⏺ Visual Mode Enhancements

  Block selection:
  - Ctrl+v - Visual block mode for column editing
  - I in visual block - Insert at beginning of all selected lines
  - A in visual block - Append to end of all selected lines

  Smart selection:
  - gv - Re-select last visual selection
  - o - Jump to other end of selection
  - U - Make selection uppercase

⏺ Powerful Macros & Registers

  Recording macros:
  - q{letter} - Start recording to register
  - q - Stop recording
  - @{letter} - Execute macro
  - @@ - Repeat last macro
  - {number}@{letter} - Execute macro n times

  Register tricks:
  - "{letter}y - Yank to specific register
  - "{letter}p - Paste from specific register
  - "0p - Paste from yank register (ignores deletes)
  - "+y / "+p - System clipboard
  - "*y / "*p - Selection clipboard

⏺ Update Todos
  ⎿  ☒ Research advanced Neovim motion and navigation techniques
     ☒ Explore text objects and selection improvements
     ☒ Find useful macro and register workflows
     ☐ Discover LSP and completion productivity tips

⏺ LSP & Completion Productivity

  Code navigation:
  - gd - Go to definition
  - gr - Go to references
  - K - Show hover documentation
  - <leader>rn - Rename symbol
  - <leader>ca - Code actions

  Completion shortcuts:
  - Ctrl+n / Ctrl+p - Next/previous completion
  - Ctrl+y - Accept completion
  - Ctrl+e - Cancel completion

  Hidden Gems

  Search & replace:
  - * / # - Search word under cursor forward/backward
  - g* / g# - Partial word search
  - :%s//new/gc - Replace last search with confirmation

  Undo/redo:
  - u - Undo
  - Ctrl+r - Redo
  - g- / g+ - Navigate through undo tree by time

  Folding:
  - za - Toggle fold
  - zR - Open all folds
  - zM - Close all folds
