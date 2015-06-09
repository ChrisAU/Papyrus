# Locution
Incomplete scrabble game written in Swift using SceneKit. This game handles all single player logic thus far, but has yet to tackle multiplayer and AI. I started this project as a learning exercise for me to improve my functional programming skills alongside Apple's relatively new Swift language.

Major Features:
* Flood fill approach to detecting touching tiles.
* Support for larger boards by using a 'symmetrical' algorithm rather than hardcoding the multiplier squares.
* Trie dictionary lookup (proposed by Appel & Guy "The World's Fastest Scrabble Algorithm", 1988).
