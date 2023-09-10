# Nerbak

## Introduction
A modern alternative to the Qwerty, Dvorak, and Colemak keyboard layouts. Designed to be a general purpose, efficent, ergonomic, and balanced layout.
Currently a WIP

## Finger Map
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/f2e45729-217e-49c4-9b47-82f1b812885c)

## Heat Map
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/4a7137bc-7abe-40fe-913b-c3e291b90581)

## History
The modern English speaking world is stuck in our ways, Everyday we interact with the most impressive tool mankind has ever created with an interface that was designed in the 1870s. There are plenty of articles and videos that delve more into the Qwerty keyboard layout and its flaws, I will not rehash them here, There are many layouts that have been created attempting to dethrown Qwerty, I have highlighted the ones below that influenced the creation of Nerbak, as well as listed their methodologies that Nerbak adopted and their flaws that Nerbak tried to avoid.

### Dvorak
Created 1936 by August Dvorak

Adopted Methodologies
1. The most common letters should be placed on the home row keys to limit total finger travel
2. All vowels should be placed on one side of the keyboard to increase alternation which anecdotally limits hand fatigue
3. Fix some of Qwerty's worst same finger bigrams (ED/DE, CE if you don't alt finger C, LO, UN, RT, CT if you do alt finger C, etc.)

Pitfalls
1. Very low similarities to Qwerty makes it more difficult to learn
2. Common computer shortcuts (ZXCV) are no longer nccessible with one hand
3. Still a high frequency of same finger bigrams (GH, E., CT, RN, UP, etc.)
4. High right hand pinky and ring finger usage 

### Colemak
Created in 2006 by Shai Coleman

Adopted Methodologies
1. High similarities to Qwerty make it far easier for Qwerty users to learn
2. Common computer shortcuts (ZXCV) retain their orinal position
3. Fix most of both Qwerty and Dvorak's worse same finger bigrams
4. Minimized ring and pinky finger usage

Pitfalls
1. The D and H keys being in the center column creates lateral shift bigrams which cause uncomfortable stretching (especially the HE bigram). Dvorak also has high frequency letters on its center column, but its natural alternation helps prevent the lateral stretch issue
2. With the focus on rolls rather than alternation there is a higher number of redirects (YOU as particularly bad example)
3. Punctuation retain their original positions in an attempt to make the layout more similar to qwerty, but the trade off is that punctuntion same finger bigrams are noticibly bad

### Workman
Created in 2010 by OJ Bucao

Adopted Methodology
1. Fingers reaching and curling are more comfortable than stretching horizontally. Most common letters are on the home keys, not the home row
2. Fingers have their natural motion taken into account. Index and Pinky fingers are shorter and prefer to curl while Middle and Ring fingers are longer and prefer to stretch. Index and Middle fingers are stronger and can handle more work while Ring and Pinky fingers are weaker and should handle less week
3. Common computer keyboard shortcuts (ZXCV) are still accessible

Pitfalls
1. Same finger bigrams are a huge step back, even worse than Dvorak (LY, E,, PO/OP, CT, ect.)

### Colemak DH
Some stuff on Colemak DH

### Nerts / Nerps
Some stuff on Nerts / Nerps

## Goals
One of the most common recommendations alternative layouts is Colemak DH. It boasts vast metric improvements on Qwerty, while being easy to learn and keeping the common shortcut keys (ZXCV) accessible.
However it is classified as a more rolling layout, with lower alternation and higher redirects. My goal with Nerbak is to create an alternative to Colemak DH that maintains or improves its metric performance, still remains easy to learn, keeps the common shortcut keys accessable, and increases alternation and limits redirects.

## Design
The base keyboard layout is Nerts. Smudge created an excellent layout that has low SFBs, SFSs, LSBs, and Redirects. Smudge also created Nerps which is a modification of Nerts and moves the P character from the pinky to the index finger. This is an excellent modification but I thought that it could be improved. Looking at other keyboard layouts like Graphite and Gallium we see that the P-B swap does help our metrics. I considered naming this inbetween step Nerbs, following the nming convention setup by Smudge.
However it wasn't until I started playing with Angle Mods for Nerbs when I noticed that the C and V characters retained their Qwerty positions. A few swaps later and I had an Angle Mod bottom left row of XMCVZ. Revert the Angle mod and you get ZXMCV. This remined me of the Colemak Dh bottom left row of ZXCDV, and the idea was born. A high alternation, low redirect alternative to Colemak DH

Nerbak Columnar
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/dd5586ec-0670-40a0-90bf-187d61d754ed)

Nerbak Angle Mod
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/06ce4c58-b810-4e27-b348-22a25ea8de14)
I would recomend the Angle Mod on an Ansi Keyboard. The row stagger creates some easier to reach keys (Qwerty T for the left hand and Qwerty N for the right) but also some harder to reach keys (Qwerty B for the left hand and Qwerty Y for the right hand).
Without the angle mod V gets put on the hardest left hand key, but with the angle mod instead it is Z. Considering 1) V is more common than Z and 2) ctrl+v is often used with the right hand on the mouse while ctrl+z is more often used with both hands on the keyboard, this seems like the correct stance.
Another benefit is that it improves the of characters that do not require a position change from Qwerty. Without the angle mod Z and X retain their position but C and V shift one key right. With the angle mod C and V retain their position and X shifts on key left, Z then gets shifted 4 keys right however C and V are more common than X and Z so keeping their Qwerty positions lowers the learning barrier more than Z and X.

## TBD
Decide on the W-B swap. Keep in mind the mb bigram for example.

## Metrics
The Nerbak layout compared to Qwerty and Colemak DH. I consider these to be the main competitors.

Oxey Playground

|   Layout   |  SFB  |  DSFB  |  LSB  |
|------------|-------|--------|-------|
|   Qwerty   | 6.615 | 11.169 | 6.882 |
| Colemak DH | 1.387 | 8.877  | 1.957 |
|   Nerbak   | 1.059 | 7.529  | 1.564 |
