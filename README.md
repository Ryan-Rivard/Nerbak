# Nerbak
A modern alternative to the Colemak DH keyboard layout. Currently a WIP

## Introduction
Nerbak is a modification of the Nerts/Nerps keyboard layouts with accessible shortcut keys ala Colemak DH

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
