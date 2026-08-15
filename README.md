# AtticaAutoInv

AtticaAutoInv is a legacy Minecraft Bukkit plugin that automatically places mined block drops directly into a player's inventory.

This project was originally developed by myself in 2015 as a commissioned project.

## Features

* **Automatic block collection**
  Mined blocks are added directly to the player's inventory instead of being dropped into the world.

* **Inventory capacity checking**
  Detects when the player's inventory is full and displays an in-game warning.

* **Fortune enchantment support**
  Adjusts the quantity of block drops when mining with the Fortune enchantment.

* **Silk Touch support**
  Preserves the original block type and data when mining with Silk Touch.

* **Automatic ore processing**
  Iron and gold ore are converted directly into iron and gold ingots when mined.

* **Ore experience rewards**
  Mining recognised ore blocks awards experience directly to the player.

* **WorldGuard integration**
  Block handling is only performed when the player has permission to build in the relevant WorldGuard region.

* **Custom item pickup feedback**
  Plays an item pickup sound when blocks are successfully added to the player's inventory.

## Technologies

* Java
* Bukkit / Spigot API
* WorldGuard API

## Compatibility

> **Note:** This project was developed against Minecraft/Bukkit APIs from 2015. It is retained as a historical project and is unlikely to work with modern Minecraft server versions without significant modification.
