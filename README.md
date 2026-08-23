# DeposteronDamageMaster

**DeposteronDamageMaster** is a lightweight Warrior rotation addon designed for WoW Vanilla/Turtle WoW-style 1.12 clients.

The addon provides a simple priority-based combat rotation through the `/ineeddeposteron` command.

## Rotation Priority

1. **Auto Attack**

   * Starts Auto Attack automatically when a valid hostile target is selected.
   * Does not toggle Auto Attack off when the command is pressed repeatedly.

2. **Battle Shout**

   * Casts Battle Shout whenever the buff is missing.

3. **Execute**

   * Used when the target is at **20% health or lower**.

4. **Bloodthirst**

   * Main damage ability used whenever available.

5. **Whirlwind**

   * Used after Bloodthirst as the next offensive priority.

6. **Heroic Strike**

   * Used when the Warrior has **50 or more Rage**.

## Command

`/ineeddeposteron`

Press the command repeatedly during combat to execute the rotation according to the current target, buffs, health percentage, cooldowns, and available Rage.

## Requirements

* Warrior class
* WoW 1.12-compatible client
* The standard **Attack** ability should be placed somewhere on the action bars so the addon can detect and start Auto Attack.

## Installation

1. Download the addon.

2. Extract the `DeposteronDamageMaster` folder into:

   `World of Warcraft/Interface/AddOns/`

3. Restart the game or reload the UI.

4. Make sure **DeposteronDamageMaster** is enabled in the AddOns menu.

5. Use `/ineeddeposteron` in combat.

## Notes

This addon is intended as a simple personal rotation helper and follows a fixed priority system rather than performing advanced combat calculations.
