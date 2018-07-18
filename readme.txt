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


TODO:
--------------------------------------------------------------------------------
. Remaining Challenges
. Bonus_Australia
. DLC_Corvi_63
. Research_Net