# MG5
## Devlog
Wei Chen, He/him

1. In my opinion, I feel like the NavMesh is more useful when characters need to find their way around a map in the game and avoid obstacles automatically. For example, in League of Legends, players click on the ground to move their characters, so using a NavMesh makes sense because it can help characters find a path to their destination. For another example, I think a game like Super Mario Bros. would work better with the physics-based movement since the player needs to jump, fall, and interact with platforms during playing. In this case, physics is more important because the character's movement depends on gravity and collisions. Overall, I think the better choice depends on how the characters are supposed to move in the game.
2. The for loop in BirdManager.cs goes through every bird in the _birds array, starting from the first bird until it reaches the end of the array. Inside the loop, Vector3.Distance is used to calculate the distance between the current bird and the player's position. Then, the if statement checks whether that distance is less than or equal to _interactDistance. If the bird is close enough, the code calls RunAway() to make it run away from the player. I learned that even though the loop checks every bird in the array, only the birds within the interaction distance will run away. This allows the birds to react when the player gets close instead of having every bird run away at the same time.

## Open-Source Assets
- [Quirky animal 3D models](https://assetstore.unity.com/packages/3d/characters/animals/quirky-series-free-animals-pack-178235)
- [Mountain fantasy environment models](https://www.fab.com/listings/60487a72-3f20-4bb2-aa78-247ed1582656)