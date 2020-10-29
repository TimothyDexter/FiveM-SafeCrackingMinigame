Disclaimer:

To utilize these file(s) you will need to strip project methods (mostly logging) and compile a .dll to use a resource on your server.  Otherwise, you are best served using the source code to derive your own implementation in the language of your choice.

[Preview](https://youtu.be/LFKCTySxm9o)

Safe cracking mini-game from GTA-V:

To use as standalone .dll:

- Create safe where you want to use minigame using props: v_ilev_gangsafe, v_ilev_gangsafedoor

Call public methods from SafeCracking:
 * InitializeSafe( int safe_entity_handle, int safedoor_entity_handle, List<int> safe_combination, DirectionEnum initialDirection)
 * RunMiniGame()
  * The result of which will indicate via an enum the result of the attempt.
 * etc...
  
This script handles the player animation of safecracking as well as the scaleform and actual minigame.
