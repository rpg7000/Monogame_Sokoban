

Impossible levels are still possible as I have not implemented a check to see if a level is solvable, for now press Y to generate a new level of equal difficulty

Controls:

    Esc: Closes the game

    Y: Generate a new level of equal difficulty (If an impossible level is created)

    F1: Load a level in the .json format

    F2: Save the current level

    W: Move one tile up

    A: Move one tile to the left

    S: Move one tile down

    D: Move one tile to the right

    Z: Undo the last move

.NET Core desktop is required download at https://dotnet.microsoft.com/download/dotnet/5.0/runtime, direct download links are below:

* [x64](https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-desktop-5.0.7-windows-x64-installer)
* [x86](https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-desktop-5.0.7-windows-x86-installer)
* [arm64](https://dotnet.microsoft.com/download/dotnet/thank-you/runtime-desktop-5.0.7-windows-arm64-installer)

I am unsure if the current release will work on any platform other than x64

Custom levels can still be made using the .ogmo file and ogmoeditor however the built-in level editor, accessible by pressing F3 is specifically designed for this game and as such is often faster to use.



Most recent release: [1.2](https://github.com/rpg7000/Monogame_Sokobon/releases/tag/v1.2)

Release History:
* [1.0](https://github.com/rpg7000/Monogame_Sokobon/releases/tag/v1.0)
  * First Release
* [1.1](https://github.com/rpg7000/Monogame_Sokobon/releases/tag/v1.1)
  * Added runtime level loading and saving
* [1.2](https://github.com/rpg7000/Monogame_Sokobon/releases/tag/v1.2)
  * Added a built in level editor and working on proceduraly generated level solvability checks
