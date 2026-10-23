# Thrink

Thrink (formerly Chain Placement) is a strategic tile placement game played on a 5x5 board. Place each tile where it counts: a tile merges when the connected group of same-numbered tiles it joins (up, down, left, right, counting the placed tile) reaches 3 or more; the group collapses into the placed tile and it doubles, and chains repeat with the new number, multiplying your score. Big tiles are volatile: once tiles reach 64, they merge in a connected group of just 2 instead of 3, so the biggest combinations stay within reach. Tiles come from a shuffled bag of 10 (seven 2s, two 4s, one 8) with the next 3 tiles visible, so you always know what is left to come. If the wrong tiles are coming up, a limited-use Shuffle button reorders only the tiles still undealt, without changing what the bag contains: you start with 1 shuffle charge, earn +1 each time you finish a bag, and can hold at most 2. The game ends when the board is full. It has two modes: Free Play with random bags, and Daily, where the bags are seeded by the date so everyone gets the same tile order that day.

The game includes an optional "How to play" tutorial for anyone who wants the rules explained, plus placement and chain sounds with a mute toggle.

Play it live: https://mphaber.github.io/chain-placement/

The `index.html` in this repository is a self-contained exported snapshot of the Muse artifact where the game was built. It has no external dependencies, and updates are published by exporting a fresh snapshot and pushing it here.
