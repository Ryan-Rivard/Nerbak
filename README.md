# Nerbak
An alternative keyboard layout specifically desgined for ANSI keyboards with modern design theories. Nerbak is a general purpose, efficent, ergonomic, and balanced alternative to the Qwerty, Dvorak, and Colemak keyboard layouts.
Currently a WIP

### Finger Map
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/6e43a65a-588b-406a-bc0c-6f14cb7ef002)

### Heat Map
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/3d9884ee-4958-4b23-870b-d18d1bbb168f)

## Goals
The primary keyboard layout we in the US deal with day to day is the ANSI standard, however it is largely recognized that the Matrix style keyboard is more ergonomic. I wanted to create a layout that would minimize the weaknesses of the ANSI keyboard for those that could not use a Matrix style keyboard (i.e. money, portability, built in laptop keyboard)

Additionally, the layout must be an improvement on Qwerty and be at least as good (if not better) than other Qwerty alternatives (Colemak, Colemak DH, and Dvorak) and retain accessibility of the commone keyboard shortcut keys (ZXCV). To read more about the the keyboard layout design theories click [here](https://docs.google.com/document/d/1_a5Nzbkwyk1o0bvTctZrtgsee9jSP-6I0q3A0_9Mzm0/edit)

Here are the metrics which Nerback tries to accomplish
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

## Design
Nerbak takes most of its inspiration from the Nerps layout which is itself a modification of the Nerts layout. The P-B switch was inspired from the Gallium/Graphite/Maya. Then X-Q-J-Z were swapped to create a ZXMCV row which is inspired from the Colemak-DH ZXCDV row.

For best use on the ANSI keyboard an angle mod was implemented to create the XMCVZ bottom row, and the K-Y switch was a result of testing finding pain from Lateral Bigram Stretch E->Y and Y->E.

### Etymology
As the Nerts / Nerps naming convention was already estabilshed, I internally refered to the P-B swap layout as Nerbs. With the Colemak-DH-esq keyboard shortcut accessibility, I added in the Colemak/Dvorak naming convention to arrive at Nerbak.

## Space Thumb
To fully optimaze Nerbak a left thumb space is assumed. Not only is it slightly right hand dominant, but it is also designed for the H + Vowels hand to be opposite of the T + Space hand. This limits redirects while increasing both rolls and redirects.

## Goals
One of the most common recommendations alternative layouts is Colemak DH. It boasts vast metric improvements on Qwerty, while being easy to learn and keeping the common shortcut keys (ZXCV) accessible.
However it is classified as a more rolling layout, with lower alternation and higher redirects. My goal with Nerbak is to create an alternative to Colemak DH that maintains or improves its metric performance, still remains easy to learn, keeps the common shortcut keys accessable, and increases alternation and limits redirects.

## Design
The base keyboard layout is Nerts. Smudge created an excellent layout that has low SFBs, SFSs, LSBs, and Redirects. Smudge also created Nerps which is a modification of Nerts and moves the P character from the pinky to the index finger. This is an excellent modification but I thought that it could be improved. Looking at other keyboard layouts like Graphite and Gallium we see that the P-B swap does help our metrics. I considered naming this inbetween step Nerbs, following the nming convention setup by Smudge.
However it wasn't until I started playing with Angle Mods for Nerbs when I noticed that the C and V characters retained their Qwerty positions. A few swaps later and I had an Angle Mod bottom left row of XMCVZ. Revert the Angle mod and you get ZXMCV. This remined me of the Colemak Dh bottom left row of ZXCDV, and the idea was born. A high alternation, low redirect alternative to Colemak DH

Nerbak Angle Mod
I would recomend the Angle Mod on an Ansi Keyboard. The row stagger creates some easier to reach keys (Qwerty T for the left hand and Qwerty N for the right) but also some harder to reach keys (Qwerty B for the left hand and Qwerty Y for the right hand).
Without the angle mod V gets put on the hardest left hand key, but with the angle mod instead it is Z. Considering 1) V is more common than Z and 2) ctrl+v is often used with the right hand on the mouse while ctrl+z is more often used with both hands on the keyboard, this seems like the correct stance.
Another benefit is that it improves the of characters that do not require a position change from Qwerty. Without the angle mod Z and X retain their position but C and V shift one key right. With the angle mod C and V retain their position and X shifts on key left, Z then gets shifted 4 keys right however C and V are more common than X and Z so keeping their Qwerty positions lowers the learning barrier more than Z and X.


## Next steps
Create a name and a repository for the following matrix keyboard layout with S on the left thumb
![image](https://github.com/Ryan-Rivard/Nerbak/assets/76035590/c1ba3566-0ebd-4507-96e5-9e1293ab30a2)


