# Unicode Characters for Chess

Documenting Unicode support for chess. I'm using New in Chess Yearbook
71 as a source what kind of characters there are. There are some
problems: compensation (infinity over equals), I'm quite sure I've seen
it somewhere in Unicode, but I couldn't spot it now. Pair of bishops is
wrong, the squares should be white instead of black.

The right solution would possibly be using SVG for all this.

Please not that NAGs over $139 are non standard and introduced by [Chesspad](http://www.wmlsoftware.com/chesspad.html). However, some of them are more useful than some of 
the overly exact standard NAGs.

## The Meaning of Annotations

Please see [Chess annotation symbols](https://en.wikipedia.org/wiki/Chess_annotation_symbols).

Symbol | Codepoint | English | NAG
------ | ---------- | ------- | ---
&#x2654; | U+2654 | White Chess King | N/A
&#x2655; | U+2655 | White Chess Queen | N/A
&#x2656; | U+2656 | White Chess Rook | N/A
&#x2657; | U+2657 | White Chess Bishop | N/A
&#x2658; | U+2658 | White Chess Knight | N/A
&#x2659; | U+2659 | White Chess Pawn | N/A
&#x265A; | U+265A | Black Chess King | N/A
&#x265B; | U+265B | Black Chess Queen | N/A
&#x265C; | U+265C | Black Chess Rook | N/A
&#x265D; | U+265D | Black Chess Bishop | N/A
&#x265E; | U+265E | Black Chess Knight | N/A
&#x265F; | U+265F | Black Chess Pawn | N/A
&#x2a72; | U+2A72 | White stands slightly better | $14
&#x2a71; | U+2A71 | Black stands slightly better | $15
&#xb1; | U+00B1 | White stands better | $16
&#x2213; | U+2213 | Black stands better | $17
+&#x2212; | U+002B U-2216 | White has a desicive advantage | $18
&#x2212;+ |  U-2216 U+002B | Black has a desicive advantage | $19
= | U+003D | Balanced position | $10; $11 or $12 might be applicable
&#x221e; | U+221E | Unclear position | $13
FIXME | FIXME | With compensation for the material – a symbol with &#x221e; over = is needed. This might be useful: https://stackoverflow.com/questions/47437061/how-to-combine-two-unicode-symbols-to-create-a-new-symbol | $44 for White, $45 for Black
&gt; | U+003E | Strong | N/A
&lt; | U+003C | Weak | N/A
&#x2265; | U+2265 | Better is | $142
&#x2264; | U+2264 | Weaker is | $143
! | U+0021 | Good move | $1
!! | ASCII | Excellent move | $3
? | ASCII | Bad move | $2
?? | ASCII | Blunder | $4
!? | ASCII | Interesting move | $5
?! | ASCII | Dubious move | $6
&#x25A1; | U+25A1 | Only move | $7
&#x25B3; | U+25B3 | With the idea | $140
&#x2B62; | U+2B62 | Attack | $40 for White, $41 for Black
&#x2B61; | U+2B61 | Iniative | $36–$39
&#x2B85; | U+2B85 | Lead in development | $30-$35
&#x2B82; | U+2B82 | Counterplay | $130-$135
&#x25E8; | U+25E8 | Kingside | $242
&#x25E7; | U+25E7 | Queenside | $243
Capital S in a square | FIXME | Space | $24–$29
Capital C in a square | FIXME | Center | $48-$53
&#x2B00; | U+2B00 | Diagonal | $240
&#x2B04; | U+2B04 | File | $239
&#x259E; | U+259E | Pair of bishops – FIXME: but the squares should be white | $246
&#x25CB;&#x25CB; | U+25CB U+25CB | Pawn structure | $249-$253
X | ASCII | Mate | N/A
N | ASCII | Novelty | $146
EN | ASCII | Endgame
Z | ASCII | Zugzwang | $22 for White, $23 for Black
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

* [Mathematical operators and symbols in Unicode](https://en.wikipedia.org/wiki/Mathematical_operators_and_symbols_in_Unicode)
* [Unicode Characters in the 'Symbol, Math' Category](http://www.fileformat.info/info/unicode/category/Sm/list.htm)
