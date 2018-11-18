SpaceChem: Solutions Archive
Gregor Ulm, 2018
================================================================================


Introduction
--------------------------------------------------------------------------------
This directory contains solutions to Zachtronic's design puzzle game SpaceChem.
It is visual programming in disguise, with a Turing-complete visual programming
language, no less. The objective of the game is to come up with procedures
(research levels) or even programs (production levels) that transform a given
input into the desired output. The challenge is two-fold: (1) using the provided
limited abstractions for your solutions, and (2) fitting them into tight spacial
constraints. Once your code works, you have the choice to make it beautiful
and/or make it fast by finding a more efficient routing of the instruction path,
using fewer symbols, or finding different approaches that may, for instance,
increase parallelism that leads to using fewer cycles. Overall, SpaceChem is a
very satisfying game if you enjoy creative problem solving. If not, you will
probably be turned off within minutes. Having a background in computer science,
in particular functional programming, is a big advantage, as the solutions you
create are all pure functions.


Solutions
--------------------------------------------------------------------------------
My solutions are organized in various folders, which contain a statistics.txt
file. Research and production levels are specified by the following data: elapsed
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

There are supposedly differences in levels that use random inputs, depending on
the used operating system and its implementation of pseudo-random numbers. I
have not looked into this in detail. Some people even claim that those no such
differences exist. In any case, I played SpaceChem on Apple macOS 10.13.
SpaceChem is no longer officially supported on that platform, so I had to use
a fan-made compatibility patch to get the game running. (Edit: In November 2018,
Zachtronics restored SpaceChem's macOS support with a patch. It is unclear if
this affects problems with random inputs in a meaningful way.)


Folders
--------------------------------------------------------------------------------
1_Extra       : Misc. screenshots
2_Save_File   : Backup of my local save file
3_Story_Mode  : Solutions to all story mode missions
4_Bonus       : Solutions to all bonus missions (Moustachium)
5_DLC         : Solutions to all DLC missions (Corvi 63)

In progress:
6_Journal     : Solutions to some JRE problems (ResearchNet)
7_Tournaments : Solutions to SpaceChem tournament problems