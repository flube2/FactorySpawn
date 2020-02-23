Demo for factory manager. There are 5 SpawnPads and 5 different animal types. There is a spawn manager that every 3 seconds, chooses a random SpawnPad, chooses a random animal, and spawns an actor of that animal class on a SpawnPad. Each animal type retains it's own mesh and unique animations. I used an abstract class ABP_Animal so that I can have an array of animals on the spawn manager and spawn an animal of any type so long as it inherits from Animal. 

Open in Unreal 4 and click Play.
