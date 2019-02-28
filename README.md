# BattleFactoryDocs

This should literally just contain two text files: BattleFactoryListBalanced.txt and BattleFactoryListRisky.txt.
These should be accessed remotely via the project itself on itch.io.

Each list should be formatted as such:
Each line of a Pokemon's export data should be after a linebreak, as the raw export data already contains. In other words, you shouldn't need to touch it. 
Parentheses, hyphens, ticks (the character that shares a key with tilde: `), and spaces are forbidden characters. The terms "Mr.", "Mime", and "Jr.", and "Mega-Rayquaza" are all forbidden terms.
  If a Pokemon's name is not appearing double-check its name for any particularly weird characters. Unicode characters are probably fine, but I know the Lenny face, for instance, throws errors.
Any Pokemon that is not the very first on the list should be prefaced by a tick (`) mark before its nickname (or species name if no nickname is present). This is what breaks Pokemon apart in the parser and separates submissions.
