# MG6
1. I think that whether a long for loop would lag the game or not depends on how the for loop is made long.
   For instance, if there were a couroutine running in the loop, or something that would yield or call for time,
   the loop would execute a step per frame. But otherwise I think that the for loop would try to run the whole
   thing every frame, causing the game to lag out.
2. An issue is that a player can get stuck inside of a platform and double jump. This is because my current logic
   has no way to check whether or not the player character fully phased up the platform.
