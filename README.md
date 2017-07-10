# pyRamDiff

This script loads an OpenAI gym environment, runs it with a random agent, and tracks the number of changes for each of the 128 bytes of the Atari memory.  The goal is to use this information as a clue to guess which memory locations are most relevant to the playing of the specific Atari game.  By considering this, one could use the most changed locations prefferentially as elements to watch and make comparisons to in atomic functions of a genetic programming program.

