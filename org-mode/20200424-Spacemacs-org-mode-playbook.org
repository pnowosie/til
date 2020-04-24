#+TITLE: Ode to Org Mode
#+DESCRIPTION: Motywacja co potrafi Org aby organizowac sie przy uzyciu Emacs

* Zostan z Emacs i naucz sie Org Mode!
(wlasnie ogladam YT: https://www.youtube.com/watch?v=PVsSOmUB7ic)

** Co potrafi Org?

  Oj duzo potrafi. Potrafi organizawac notatki w drzewa i poddrzewa, poruszac
  sie pomiedzy nimi, przemieszczac cale drzewa, exportowac do HTML-a, PDF ...
  GitHub konwertuje Org do HTML - rowniez z obrazkami.
  Prezentacje reveal.js

  Tabele, wczytywanie danych csv, formuly i iczenia na danych, wykresy (gnu-plot).
  Literate programming, tekst, snippety kodu, uruchamianie kodu by dodac wyniki.
  Klient do bazy postgres.
  
  Zarzadzanie projektami i taskami, tracking czasu. W tym w dowolnym pliku z kodem 
  (feat: Org-capture) mozna dodac TODO i bedzie on widoczny z agendy.

** Skroty trzeba cwiczyc
   
   Nie uzywamy polskiej czcionki bo tu sa magiczne skroty ukryte pod nimi
   
   Na przyklad: 
*** M-o - dodaje ponizej subnode
*** C-<Enter> - dodaje node tego samego poziomu
*** C-<Shift>-<Enter> - dodaje TODO ponizej na tym samym poziomie
*** C-<Shift>-strzalka -> - promuje do TODO
*** M-<Enter> - w srodku zdania promuje reszte od kusora do konca do node
*** M-t - dodaje `TODO` item na obecnym poziomie tree
*** M-h - zmienia obecny poziom na wyzszy (M-strzalka >)
*** M-l - zmienia obecny poziom na nizszy (M-strzalka >)
*** M-(strzalki UP / DOWN) - zmienia kolejnosc wsrod node swojego poziomu
*** M-k - przenosi (zamienia) obecny node w gore (M-strzalka ^)
*** M-j - przenosi (zamienia) obecny node w dol (M-strzalka v)
*** M-s - ma pod soba isearch np: `M-s .` wyszukuje symbol pod kursorem
*** Ciekawostka: `M-u` zmienia litery od kursora do konca slowa na UPPER
*** Ciekawostka: `M-c` zmienia litere pod kursorem na wielka
** I duzo praktyki
   
*** Toggle Zen (distraction free) mode - `SPC-w-c` 
*** C-<Shift>-l - opcje skupienia (srodek - gora - calosc)
*** Toggle Line numbers `SPC-t-n`, w tym relative numbers `SPC-t-r`
*** Dedykowane komendy Org mode w Spacemacs sa pod `SPC-m`
    Na przyklad by wypromowac tekst na node najblizszego poziomu przejdz na 
    poczatek tekstu

    -> o tutaj sprobuj

    I teraz: 
****  SPC-m-h-I - promocja do odecnego
****  SPC-m-h-I - promocja do subnode

*** Operacje na nodach z `z`

**** `zc` - close node
**** `zo` - open node
**** `zr` - enfold everything (rozwin wszystko)
**** `zm` - fold everything (zwin wszystko)

*** Operacje na subtree

**** SPC-m-S - opcja dla calego poddrzewa
***** h, l - promote / demote
***** j, k - move (entire) subtree down / up
** Operacje tekstowe
*** SPC-x - opcje w spacemacs
*** ,-x - opcje w Org mode
**** ,-x-b - *bold*
**** ,-x-i - /italic/
**** ,-x-s - +strike through+
**** ,-x-u - _underline_
**** ,-x-v - =verbose=
**** ,-x-c - ~code fragment~
**** ,-x-r - clear *previously* used formating
