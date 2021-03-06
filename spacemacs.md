Tutorials
---

- [Spacemacs docs](https://github.com/syl20bnr/spacemacs/tree/master/doc)
- [Seoren videos yt](https://www.youtube.com/channel/UCsJXkw_Ssp-1myJFm4_SMJA)
- [Spacemacs ABCs yt](https://www.youtube.com/playlist?list=PLrJ2YN5y27KLhd3yNs2dR8_inqtEiEweE)
- [Spacemacs keybindings](https://gist.github.com/pnowosie/b5f7cf9f6df09cc9f0e797cd2350971c)

VIM Basics
---

- hjkl - moving cursor
- C-f / C-b - scroll page fwd (down) / bwd (up)
- C-d (down) / C-u (up) - scroll half page


- S bd - buffer del
- S wd - window del

- S qq - quit spacemacs


ADM
---
- S fed - find dotfile
- S fe R - sync config install new packages

- S fs - file save

- S zf - transient zoom +/- font size


NAVIGACJA
---
- S pf - fuzzy file find, e.g. "sta co" - podpowiada state/core
- S ff - find file

- S bb - change buffer with helm
- S b 1-9 buffer change


EDYCJA
---
- SPC cl - un/comment line
- gg - jump beggining of the file
- o - new line and insert mode (below cursor)
- O - new line and insert mode (above cursor)

- SPC x J - move current line down (or several lines while selected with `V`)
- SPC x K - move current line down

### Indentation (Wciecie)
- `>` (x2) - indents
- `<` (x2) - oudents

### copy text, paste, cut
- Position the cursor where you want to begin cutting.
- Press v to select characters (or uppercase V to select whole lines, or Ctrl-v to select rectangular blocks).
- Move the cursor to the end of what you want to cut.
- Press d to cut (or y to copy).
- Move to where you would like to paste.
- Press P to paste before the cursor, or p to paste after.

FIND & REPLACE
---

### Inside a buffer
- Vim style `:%s/"co"/"na co`
- inline change (with curson in Symbol) type `#` then `i` and use vim keys to edit

### Global
Use `SPC /` for global search or if the searching Symbol is in the buffer highlight it with `#` then `/`
to show results

(don't hit <Enter>) `C-c C-e` makes result buffer editable, so buffer replace tricks are working 
  when ready to global replace `C-c C-C` 

GIT magit !!!
---
SPC g s - git status

[Great desc of available commands](https://www.saltycrane.com/blog/2018/11/magit-spacemacs-evil-magit-notes/#status)


Co bym sie chcial dowiedziec?
---

- szybka navi po plikach
- otwieranie plikow w buffor
- jak szukac skrotow klawiat
- jak otwierac terminal
- jak nawigowac w wbudowanym eksploratorze
- bookmarks
-

Poza tym?
---
- Org mode
- Code templates
- Insert curr date

More
---
- how to operate on files: copy/rename/move
- how to git: pull, commit, push, repo init
