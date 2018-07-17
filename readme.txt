SpaceChem: Solutions Archive
Gregor Ulm, 2018
================================================================================


Introduction
--------------------------------------------------------------------------------

This directory contains solutions to Zachtronic's design puzzle game SpaceChem.
Research and production levels are specified by the following data: elapsed
cycles, reactors used, and symbols used. The provided video files were
originally recorded in-game and later on transcoded into H.265 to save space.
Defense missions cannot be recorded. For these, screenshots describing the
solutions are provided.

In general, my solutions focus on minimizing cycles as opposed to
underutilizing the available material. In fact, I don't view minimizing for
symbols an attractive metric. For instance, in some levels it is possible to 
process the inputs in parallel. By only using one "waldo", you cut the number 
of symbols used in half while doubling your cycle count. For some production 
levels, I have attempted to reduce the number of reactors, if it made sense. 
Sometimes, this led to less efficient but aesthetically more pleasing solutions.
I would have liked to also see a metric that captures the area used, as I tend 
to find more compact solutions more appealing than others.

Almost all my solutions are very good, measured by the provided in-game metrics.
That being said, some of my favorite solutions are more due to personal
stylistic preferences. For instance, I don't like to overuse the "sync"
operator. Some of my favorite puzzle solutions are lock-free, i.e.
collaborating waldos don't use that operator at all. I also like clear solutions
more than convoluted ones. In some of the later levels, the play area is very
cramped, so there are limits to how clear your solution can be. Occasionally,
I provide alternative solutions. These illustrate different approaches or
interesting improvements over the initial solution. Lastly, there are several 
known glitches in SpaceChem that can be exploited by the user to produce faster
solutions. I have not resorted to any of those.

There are supposedly differences in levels that use random inputs, depening on
the used operating system and its implementation of pseudo-random numbers. I
have not looked into this in detail. Some people even claim that those no such
differences exist. In any case, I played SpaceChem on Apple macOS 10.13.
SpaceChem is no longer officially supported on that platform, so I had to use
a fan-made compatibility patch to get the game running.



Directories
--------------------------------------------------------------------------------

. A_Story_Mode
.. 1_Sernimir_II
.. 2_Sernimir_IV
.. 3_Danopth
.. 4_Alkonost
.. 5_Sikutar
.. 6_Hephaestus_IV
.. 7_Atropos_Station
.. 8_Flidais
TODO:
.. 9_<UNKNOWN SYSTEM>
. B_Bonus_Australia
. C_DLC_Corvi_63
. D_Research_Net


Statistics
--------------------------------------------------------------------------------

A) Story Mode

Sernimir II:
1.1 Of Pancakes and Spaceships
  a: 98, 1, 19
  b: 61, 1, 16
1.2 Slightly Different
  a: 74, 1, 16
1.3 Crossover
  a: 192, 1, 18
  b: 159, 1, 16
1.4 An Introduction to Bonding
  a: 161, 1, 18
  b: 119, 1, 17
1.5 A Brief History of SpaceChem
  a: 119, 1, 16
1.6 Removing Bonds
  a: 38, 1, 18

Sernimir IV:
2.1 Double Bonds
  a: 118, 1, 19
2.2 Best Left Unanswered
  a: 175, 1, 22
  b: 127, 1, 22
2.3 Multiple Outputs
  a: 119, 1, 17
2.4 An Introduction to Pipelines
  a: 407, 0, 0
2.5 There's Something in the Fishcake
  a: 571, 1, 18
2.6 Sleepless on Sernimir IV
  a: 823, 2, 38

Danopth:
3.1 Every Day is the First Day
  a: 295, 1, 32
  b: 234, 1, 28
3.2 It Takes Three
  a: 287, 1, 26
  b: 181, 1, 24
3.3 Split Before Bonding
  a: 208, 1, 25
  b: 254, 1, 24
  c: 158, 1, 24
3.4 Settling into the Routine
  a: 832, 3, 61
3.5 Nothing Works
  a: 538, 4, 114
3.6 Challenge: In-Place Swap
  a: 1542, 2, 62
  b: 1344, 2, 60
  c: 1342, 2, 63
3.7 A Most Unfortunate Malfunction

Alkonost:
4.1 An Introduction to Sensing
  a: 156, 1, 28
4.2 Prelude to a Migraine
  a: 210, 1, 17
4.3 Random Oxides
  a: 398, 1, 30
4.4 No Ordinary Headache
  a: 1549, 2, 50
  b: 3216, 1, 57
4.5 No Thanks Necessary
  a: 1880, 4, 91
4.6 Challenge: Going Green
  a: 2856, 4, 170
4.7 No Need for Introductions

Sikutar:
5.1 Ice to Meet You
  a: 87, 1, 24
5.2 Under the Ice
  a: 200, 1, 33
  b: 258, 1, 49
  c: 197, 1, 31
5.3 Unknown Sender
  a: 524, 1, 29
  b: 245, 1, 37
5.4 Falling
  a: 3403, 3, 106
  b: 2415, 2, 86  
5.5 Challenge: Applied Fusion
  a: 2550, 4, 125
5.6 Exploding Head Syndrome

Hephaestus IV:
6.1 Like a Boss
  a: 338, 1, 33
6.2 Sacré Bleu!
  a: 288, 1, 36
  b: 207, 1, 28
6.3 The Plot Thickens
  a: 1029, 1, 58
  b:  970, 1, 54
6.4 Danger Zone
  a: 349, 1, 22
  b: 209, 1, 35
6.5 Molecular Foundry
  a: 4678, 3, 129
6.6 Gas Works Park
  a: 1022, 5, 164
TODO: 6.7 Challenge: KOHCTPYKTOP
6.8 More than Machine

Atropos Station:
7.1 The Blue Danube
  a: 216, 1, 39
7.2 No Stomach for Lunch
  a: 326, 1, 37
  b: 313, 1, 37
7.3 No Employment Record Found
  a: 842, 1, 82
7.4 Right All Along
  a: 1639, 1, 59
7.5 Accidents Happen
  a: 705, 1, 84
7.6 Don't Fear the Reaper

Flidais:
8.1 Special Assignment
  a: 658, 1, 56
8.2 Suspicious Behavior
  a: 3052, 1, 62
8.3 I Told You So
  a: 1267, 1, 54
  b: 1018, 1, 59
8.4 Ω-Pseudoethyne
  a: 2534, 2, 131
8.5 Σ-Ethylene
  a: 8291, 2, 133
  b: 5982, 2, 121
8.6 Freedom of Choice

<UNKNOWN SYSTEM>:
TODO: 9.1 End of the Line

TODO: Challenges

TODO (?):
B) Bonus: Australia
C) DLC: Corvi 63
D) Research Net