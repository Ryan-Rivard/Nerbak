# Nerbak
An easy to use alternative keyboard layout implemented with modern design theories. Designed to be a general purpose, efficent, ergonomic, and balanced alternative to the Qwerty, Dvorak, and Colemak keyboard layouts.
Currently a WIP

### Finger Map
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/f2e45729-217e-49c4-9b47-82f1b812885c)

### Heat Map
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/4a7137bc-7abe-40fe-913b-c3e291b90581)

### ANSI Layout with Angle Mod
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/1c7d2e2a-80da-43c7-953b-e64f43d03e28)

## Goals
Read more about the the design theories [here](https://docs.google.com/document/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/edit)

- High alternation
- High rolls
- Low redirects
- Low Bigrams and Skipgrams
- Low Ring and Pinky finger usage
- Common Keyboard shortcuts (ZXCV) remain accessible
- Easy to learn

## Metrics
The Nerbak layout compared to Qwerty, Dvorak, Colemak, and Colemak DH. I consider these to be Nerbak's main competitors. Metrics generated by KeySolve.

### Balance
Balance is difficult to compare and contrast across multiple layouts as the raw data can be overwhelming. I propose a different way of measuring each layout
1. Left Right balance - are the keys separated to create an even usage split between the hands
2. Left Right Weak and Left Right Strong balance - are the weak fingers (Pinky and Ring) on one hand balanced compared to the other? And same with the strong fingers (Index and Middle)
3. Weak Strong Balance - What is the balance of work between all Weak fingers and all Strong fingers. This does not have a subjectively correct answer, but will help us see each layouts requirement for strong and/or dexterous Pinky and Ring fingers

ORRRRRR we could look at it like this
- Balance between hands
  - left / right
  - left weak / right weak
  - left strong / right strong
  - left min / right min
  - left max / right max
- Balance within each hand
  - left weak / left strong
  - right weak / right strong
  - left min / left max
  - right min / right max

#### Left Right Balance
Represented here as 1 - (Left hand usage / Right hand usage). Closer to 0 means more balanced, positive numbers are Right hand dominant, negative numbers are Left hand dominant

|   Layout   | L/R Ratio |
|:----------:|:-----:|
|   Qwerty   | -0.229 |
|   Dvorak   | 0.137 |
| Colemak (DH) | 0.199 |
|   Nerbak   | 0.125 |

Qwerty can be seen to be the least balanced with a left hand bias, wheras Nerbak is the most balanced with a slight right hand bias

#### Left Right Strength Balance
Represented here as 1 - (Left Weak finger usage / Right Weak finger usage) and 1 - (Left Strong finger usage / Right Strong finger usage) where Weak fingers are the Pinky and Ring and the Strong fingers are the Index and Middle. Once again closer to 0 means more balanced, positive numbers mean a Right side finger dominant and negative numbers for Left side finger dominant

|   Layout   | Weak L/R  | Strong L/R |
|:----------:|:-----:|:-----:|
|   Qwerty   | -0.021 | -0.339 |
|   Dvorak   | 0.241 | 0.057 |
| Colemak (DH) | 0.170 | 0.214 | 
|   Nerbak   | 0.163 | 0.103 | 

Nerbak has has the most consistent balance (explain this better) 

### Hand Balance
Note: Colemak and Colemak DH have the same hand and finger balance, they are combined for these next three tables for ease of consumption

|   Layout   | Left  | Right |
|:----------:|:-----:|:-----:|
|   Qwerty   | 55.13 | 44.87 |
|   Dvorak   | 46.31 | 53.69 |
| Colemak (DH) | 44.46 | 55.54 | 
|   Nerbak   | 46.66 | 53.34 | 

Nerbak is the most balanced of the group with Dvorak a close second. But Dvorak has its own balancing issues that I will try to illuminate next

### Finger Balance

|   Layout   |  LP  |  LR  |  LM   |  LI   |  RI   |  RM   |  RR   |  RP  |
|:----------:|:----:|:----:|:-----:|:-----:|:-----:|:-----:|:-----:|:----:|
|   Qwerty   | 7.63 | 8.28 | 18.13 | 21.09 | 20.61 | 8.67 | 13.96 | 1.63 |
|   Dvorak   | 8.24 | 9.55 | 13.96 | 14.56 | 16.90 | 13.35 | 13.36 | 10.08 |
| Colemak (DH) | 7.63 | 7.83 | 10.18 | 18.82 | 20.00 | 16.91 | 10.46 | 8.16 |
|   Nerbak   | 6.99 | 9.70 | 15.06 | 14.90 | 12.43 | 20.97 | 10.84 | 9.11 |

While messy we can see that the Qwerty balance is completely disfunctional, and Dvorak having right middle and ring fingers with identical usage is not great

### Finger Balance Ratio
I have created this table to show how each layout usage is for its strong (Index and Middle) and weak (Ring and Pinky) fingers. Hopefully it is more consumable than the previous table

|   Layout   |  LW  |  LS  |  RS   |  RW   |
|:----------:|:----:|:----:|:-----:|:-----:|
|   Qwerty   | 15.91 | 39.22 | 29.28 | 15.59 |
|   Dvorak   | 17.79 | 28.52 | 30.25 | 23.44 |
| Colemak (DH) | 15.46 | 29.00 | 36.91 | 18.62 |
|   Nerbak   | 16.69 | 29.96 | 33.40 | 19.95 |

Qwerty has a large imbalance between the Left Strong fingers and the Right Strong fingers of almost 10 percent

Dvorak has an imbalance for the Right Weak fingers with it closer to the Left Strong fingers than the Left Weak fingers (5.56 vs 5.08)

Colemak, like Qwerty has an imbalance between the strong fingers but the inverse with the Right Strong fingers getting a larger workload of almost 8 percent

Nerbak is very balanced with ~3% higher usage from both Left Weak to Right Weak and from Left Strong to Right Strong fingers

### Bigrams
- Same Finger Bigram (SFB): Using the same finger to key two letters in a row, considered very slow and should be limited as much as possible
- Lateral Stretch Bigram (LSB): Reaching the index finger to a center column letter immedately before or after a middle finger letter on the same hand, limiting can improve typing comfort
- Half-Scissor Bigram (HSB): Two finger bigram where the outside finger is one row lower than the inside finger (either top and home row or home and bottom row)
- Full-Scissor Bigram (FSB): Two finger bigram where the outside finger is on the bottom row and the inside finger is on the top row
  
|   Layout   | SFB  | LSB  | HSB  | FSB  |
|:----------:|:----:|:----:|:----:|:----:|
|   Qwerty   | 5.81 | 6.76 | 7.11 | 1.05 |
|   Dvorak   | 2.62 | 1.17 | 6.11 | 0.14 |
|   Colemak  | 1.49 | 3.48 | 6.07 | 0.37 |
| Colemak DH | 1.49 | 2.21 | 5.93 | 0.37 |
|   Nerbak   | 1.07 | 2.03 | 3.00 | 0.26 |

### Skipgrams
Same definitions as the above bigrams, however the two letters are separated by any number of other letters on other fingers. The lower the number the longer the time and the less distance for your finger to travel to that second letter
  
|   Layout   |  SFS  | LSS  | HSS  | FSS  |
|:----------:|:-----:|:----:|:----:|:----:|
|   Qwerty   | 11.67 | 8.10 | 7.07 | 1.35 |
|   Dvorak   | 7.00  | 4.48 | 8.56 | 1.22 |
|   Colemak  | 7.95  | 2.59 | 6.49 | 0.69 |
| Colemak DH | 7.95  | 1.75 | 6.49 | 0.78 |
|   Nerbak   | 7.16  | 2.87 | 7.15 | 0.64 |

### Trigrams
- Alternation (ALT): When the hands alternate over three keypresses (RLR or LRL)
- Roll (ROL): When one hand presses two keys before or after a keypress by the other hand (RRL, LRR, LLR, or RLL)
- Onehand (ONE): When all three keypresses are pressed with the same hand and all roll in one direction (Out -> In or In -> Out)
- Redirect (RED): When all three keypresses are pressed with the same hand and do not roll in one direction (Out -> In -> Out or In -> Out -> In)

|   Layout   |  ALT  |  ROL  | ONE  | RED  |
|:----------:|:-----:|:-----:|:----:|:----:|
|   Qwerty   | 24.29 | 35.73 | 2.27 | 5.51 |
|   Dvorak   | 41.70 | 37.19 | 0.43 | 2.25 |
|   Colemak  | 27.58 | 42.78 | 2.45 | 6.74 |
| Colemak DH | 27.58 | 42.78 | 2.45 | 6.74 |
|   Nerbak   | 38.47 | 42.45 | 2.41 | 1.68 |

## Etymology
Nerbak takes most of its inspiration from the Nerps layout which is itself a modification of the Nerts layout. The P-B switch was inspired from the Gallium / Graphite / Maya layouts. And the X-Q-J-Z swap to create the ZXMCV row was insipired by the Colemak-DH ZXCDV row,

As the Nerts / Nerps naming convention was already estabilshed, I internally refered to the P-B swap layout as Nerbs. Add in the Colemak-DH-esq keyboard shortcuts and I added in the Dvorak / Colemak naming convention to arrive at Nerbak.

## Optional Modifications
1. W-B swap
2. Z-V swap on columnar
3. J-/ swap especially on ansi
4. '-/ swap
5. J-/-' swap
6. K-Y / F-Y swap on ansi

## Space Thumb
To fully optimaze Nerbak a left thumb space is assumed. Not only is it slightly right hand dominant, but it is also designed for the H + Vowels hand to be opposite of the T + Space hand. This limits redirects while increasing both rolls and redirects.

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
