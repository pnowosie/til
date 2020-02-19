Dired mode
---

[This is great summary in SO](https://emacs.stackexchange.com/questions/34765/how-to-learn-dired-in-evil-mode)

Note that 'marking' files lets you operate on multiple files at once when e.g. copying or moving files.

 -  `RET` or `f` Open file or directory
 -  `o` Open file in a separate window
 -  `^` Up directory
 -  `+` Create a directory
 -  `R` Rename / move
 -  `C` Copy
 -  `M` Change file/directory mode (unix file/directory permissions)
 -  `d` Delete
 -  `m` Mark
 -  `u` Unmark / undelete
 -  `x` 'Expunge' -- i.e. actually delete files/directories marked for deletion

To create a file just open a new buffer (SPC b N) and save (SPC f s) it wherever you want
## How to get help about the mode?

Here are a few things you can try to see available keys:

? -- actually this is partly wrong because

SPC ? dired

F1 m (describe-mode)

SPC h SPC dired -- this lets you jump to the code for the layer that configures dired, spacemacs-base, which for key bindings purposes is mostly about keys to run dired rather than once you're using dired

Here are some dired keys I find useful (in fact nearly all are the same as in stock emacs, so you can also just read the info page with F1 i and much of it will correct key bindings still -- follow menus using m to go to Emacs -> Dired).
