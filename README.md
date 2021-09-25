# InfiniteMatrix

Developed with Unreal Engine 4

This is the first assignment for CS498-Game Development at the University of Illinois Urbana-Champaign.
The goal of this project was to follow this tutorial: https://www.raywenderlich.com/454-how-to-create-a-simple-game-in-unreal-engine-4.

After the tutorial, I added basic health packs, enemies, and player projectiles.
Upon collision with a health pack, player health increases.
Upon collision with an enemy, player health and player points both decrease.
Upon projectile collision with health pack, the health pack is destroyed.
Upon projectile collision with an enemy, the enemy is destroyed and player points increases.
There is a short cooldown on shooting projectiles, but no HUD indication of this feature exists as of now.
Depending on various thresholds of player health, the wall colors will change between green, organge, and red.
