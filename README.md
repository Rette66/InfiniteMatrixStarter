# InfiniteMatrixStarter

1. follow tutorial: https://www.kodeco.com/454-how-to-create-a-simple-game-in-unreal-engine-4
2. Add a health system for the player. 
   * Be displayed as a bar or number on the UI
   * Decrease their health value upon collision with an obstacle
     * If player hits an obstacle, they should then pass through the obstacle and their health should be decremented.
   * Stop the player only when their health value this 0
   * Have a max health value
   * Correctly reset to its max health value when the game is restarted
     
3. Add a score.
   * Be displayed as a number on the UI
   * Increment only when the player successfully goes through a hole in an obstacle
   * Reset to 0 when the game is restarted

4. Add health packs.
   * Be a collidable object
   * Be destroyed upon collision with the player
   * Be destroyed shortly after if the player goes past them
   * Increase the health value upon collision with the player, up to a max health value\
   * Appear in tunnels at a randomized rate, but never more than once per tunnel
   * Have a semi randomized location in the tunnel that does not collide with other objects
   
5. Add player projectile attacks.
   * Create a projectile on left mouse click that shoots forward down the tunnel faster than the player
   * The projectile is destroyed upon collision with anything and after a short duration
   * The projectile is created at the player/mouse position

6. Add enemies.
   * Be a collidable object
   * Be destroyed on collision with projectiles or the player
   * Increase the score on destruction by a projectile
   * Decrease the health value on collision with the player
   * Be destroyed shortly after if the player goes past them
   * Similar to the health pack, this can be implemented in a variety of ways.
   * enemy visually distinguishable from the health pack

7. Increase the player speed over time.


8. Add one creative modification that is unique to your game.
   * Health bar decreases along a gradient of colors
      * The gradient should constantly update according to the player’s current health (not just set the color based on certain thresholds)
