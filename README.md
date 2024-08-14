# DRR-Powerups
Powerup System Demo for DRR

Notes: 
- 

- There are two types of powerups. **STUFF** and **POWERUPS**. 
> **STUFF** category has powerups that are used in the main menu mostly. They usually improve some stats for the next dungeon or for a time period. 2 Outliers are Retraining token and Health Bomb.

> Other category is **POWERUPS**. They are equipped before the dungeon, but used inside the dungeon.

- These two categories are divided as “**PROGRESSION**” *(for STUFF)* and “**CONSUMABLE**” *(for POWERUPS)* in the JSON file.

Missing:
-
- - [ ] Need to find examples of equipped power ups getting used (Consumables). And find out if multiple can be equipped.

- - [ ] Find usages of strange shroom and take notes of the effects.

- - [ ] Find usages of consumable bombs.

- - [ ] Defense Booster giving mana is unrelated. Need to find the problem.

- - [x] Dingle Token

- - [ ] Luck Booster values need to be determined. 

All Items that are a part of this system:
-
## **Stuff**


- **Retraining Token:** Redo the Stat Point placement for 1 Hero.

- **Health Bomb:** Revives you to full health & damages enemies.

- **Party Bomb (outside of JSON):** Revives party to full health and damages enemies.

- **Luck Booster (Minor – Regular – Major):** Drink to gain better Item Drop rolls for the next Dungeon.

- **Speed Booster:** Increases movement speed by 20% for the next Dungeon

- **Power Booster:** Increases attack damage by 20% for the next Dungeon

- **Defense Booster:** Increases max mana and mana regen by 25% for the next Dungeon **(??????????)**

- **Health Booster:** Increases max health by 20% for the next Dungeon.

- **Mana Booster:** Increases max mana by 50% for the next Dungeon.

- **Buster Booster** (there is two of these with exactly same stats except name and “StoreSort” number value): Earn dungeon buster points 50% faster for the next Dungeon

- **Double Coin Booster (Potion - Regular – Major - Epic): Potion:** 2x coins for next dungeon. **Regular:** Double coins for 30 minutes. **Major:** 4x coins for 15 minutes. **Epic:** 10x coins for 7.5 minutes.

- **Party Bomb:** Revives party to full health & damages enemies.

- **Dingle Token: ????**

- **Double XP Booster (Regular – Major – Epic) Regular:** Double exp for 1 hour. **Major:** 4x Exp for 30 mins. **Epic:** 10x exp for 15 minutes.


## **Powerups**

- **Health Potion:** Heals for 100%.

- **Health Keg:** Heals for 100%, also heals allies.

- **Mana Potion:** restores 100% of mana.

- **Mana Keg:** restores 100% of mana, also for allies.

- **Ye Olde Explosive:** Blows up, stunning and damaging enemies.

- **Move Speed-Up:** Increases move speed by 50% for 30 seconds.

- **Attack Power-Up:** Increases damage dealt by 100% for 30 seconds.

- **Attack Speed-Up:** Increases attack speed by 100% for 30 seconds.

- **Defense-Up:** Increases defense for 60 seconds.

- **Buster Potion:** Refills your Dungeon Buster Points.

- **Party Move Speed-Up:** Increases move speed by 50% for 30 seconds for user and nearby allies.

- **Party Attack Power:** Increases damage dealt by 100% for 30 seconds for user and nearby allies.

- **Party Attack Speed-Up:** Increases attack speed by 100% for 30 seconds for user and nearby allies.

- **Party Defense-Up:** Increases defense for 60 seconds for you and your nearby allies.

- **Buster Keg:** Refills Dungeon Buster for you and your allies.

- **Strange Shroom: (??????)** Mysterious fungus.

- **Health Shot:** Use to heal 25% of max health.

- **Mana Shot:** Use to restore 15 mana.

- **Buster Shot:** Use to fill up a bit of your Dungeon Buster.

- **Small Shroom: (??????)** Mysterious small fungus.

- **Strange Party Shroom: (??????)** Mysterious fungus, also for allies.

- **Small Party Shroom: (??????)** Mysterious small fungus, also for allies.

- **Stranger Shroom: (??????)** Mysterious fungus with more effects (?).

- **Ye Olde Freeze Bomb:** Blows up, freezes and damages enemies.

- **Ye Olde Fire Bomb:** Blows up, burns and damages enemies.

- **Ye Olde Volt Bomb:** Blows up, shocks and damages enemies.

- **Ye Olde Poison Bomb:** Blows up, poisons and damages enemies.

- **Thirst Oasis Potion:** Restores 100% of health and mana.


## Mushroom Notes 

On “Attack” category, there are different effects for “Star Mushroom Potion Attack” and “Small Mushroom Potion Attack” (party version exists for both.).

- One that buffs allies

- One that buffs enemies

- One that is prank (Also buffs enemies)

On “Offers” category, there are small and big shrooms offered (from boxes).

- **6 Small Shrooms:** Become tiny and fast. (with party version)

- **6 Strange Shrooms:** Grow big and strong. (with party version)

- **Shrinky Shroom:** Become tiny and move and attack incredibly fast. Gain Buster faster. (after this item is unboxed, it becomes small shroom.) (with party version)

- **Consumable Star Mushroom Potion 3x:** Grow huge and deal super damage to all enemies for 30 seconds. (with party version)
