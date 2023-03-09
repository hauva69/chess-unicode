# Unicode Characters for Chess

Documenting Unicode support for chess. I'm using New in Chess Yearbook
71 as a source what kind of characters there are. There are some
problems: compensation (infinity over equals), I'm quite sure I've seen
it somewhere in Unicode, but I couldn't spot it now. Pair of bishops is
wrong, the squares should be white instead of black.

The right solution would possibly be using SVG for all this.

Symbol | Codepoint | English
------ | ---------- | -------
&#x2654; | U+2654 | White Chess King
&#x2655; | U+2655 | White Chess Queen
&#x2656; | U+2656 | White Chess Rook
&#x2657; | U+2657 | White Chess Bishop
&#x2658; | U+2658 | White Chess Knight
&#x2659; | U+2659 | White Chess Pawn
&#x265A; | U+265A | Black Chess King
&#x265B; | U+265B | Black Chess Queen
&#x265C; | U+265C | Black Chess Rook
&#x265D; | U+265D | Black Chess Bishop
&#x265E; | U+265E | Black Chess Knight
&#x265F; | U+265F | Black Chess Pawn
&#x2a72; | U+2A72 | White stands slightly better
&#x2a71; | U+2A71 | Black stands slightly better
&#xb1; | U+00B1 | White stands better
&#x2213; | U+2213 | Black stands better
+&#x2212; | U+002B U-2216 | White has a desicive advantage
&#x2212;+ |  U-2216 U+002B | Black has a desicive advantage
= | U+003D | Balanced position
&#x221e; | U+221E | Unclear position
FIXME | FIXME | With compensation for the material – a symbol with &#x221e; over = is needed. This might be useful: https://stackoverflow.com/questions/47437061/how-to-combine-two-unicode-symbols-to-create-a-new-symbol
&gt; | U+003E | Strong
&lt; | U+003C | Weak
&#x2265; | U+2265 | Better is
&#x2264; | U+2264 | Weaker is
! | U+0021 | Good move
!! | ASCII | Excellent move
? | ASCII | Bad move
?? | ASCII | Blunder
!? | ASCII | Interesting move
?! | ASCII | Dubious move
&#x25A1; | U+25A1 | Only move
&#x25B3; | U+25B3 | With the idea
&#x2B62; | U+2B62 | Attack
&#x2B61; | U+2B61 | Iniative
&#x2B85; | U+2B85 | Lead in development
&#x2B82; | U+2B82 | Counterplay
&#x25E8; | U+25E8 | Kingside
&#x25E7; | U+25E7 | Queenside
FIXME | FIXME | Space
FIXME | FIXME | Center
&#x2B00; | U+2B00 | Diagonal
&#x2B04; | U+2B04 | File
&#x259E; | U+259E | Pair of bishops – FIXME: but the squares should be white
&#x25CB;&#x25CB; | U+25CB U+25CB | Pawn structure
X | ASCII | Mate
N | ASCII | Novelty
EN | ASCII | Endgame
Z | ASCII | Zugzwang
T | ASCII | Time
– | U-8211 | See
RR | ASCII | Editorial comment
YB | ASCII | Yearbook
ch | ASCII | National championship
zt | ASCII | Zonal tournament
izt | ASCII | Interzonal tournament
ct | ASCII | Candidates tournament
ol | ASCII | Olympiad
m | ASCII | Match
cr | ASCII | Correspondence
jr | ASCII | Junior

## Sources

* [Chess Symbols](http://www.unicode.org/charts/PDF/U1FA00.pdf)
* [Mathematical operators and symbols in Unicode](https://en.wikipedia.org/wiki/Mathematical_operators_and_symbols_in_Unicode)
* [Unicode Characters in the 'Symbol, Math' Category](http://www.fileformat.info/info/unicode/category/Sm/list.htm)
