---
type: pc
race: "Giant (titan)"
class:
 - "Scion of Surtur"
subClass:
 - "CR 25"
cover: "Scion of Surtur.png"
campaign:
locations:
tags:
  - race/titan
  - affinity/hostile
  - type/giant
  - size/gargantuan
  - cr/25
  - source/bgg
---
###### Scion of Surtur
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Scion of Surtur.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 25 (75,000 XP) |
> | :RiSwordFill: Type | Gargantuan Giant (titan) |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 546 (28d20 + 252) |
> | :FasUserGroup: Race | Giant (titan) |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 30 | 17 | 28 | 21 | 24 | 20 |
| **Mod** | +10 | +3 | +9 | +5 | +7 | +5 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 25
**Languages:** Giant, Primordial
**Saving Throws:** Dex +11, Cha +13
**Skills:** Athletics +18, Perception +15
**Damage Resistances:** cold; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; petrified

---

### Traits

**Legendary Resistance (6/Day).** If the scion fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The scion has advantage on saving throws against spells and other magical effects.

**Siege Monster.** The scion deals double damage to objects and structures.


---

### Actions

**Multiattack.** The scion makes one attack using Lava Blade or Lava Ball, as well as two Slam attacks.

**Lava Blade.** Melee Weapon Attack: +18 to hit, reach 30 ft., one target. *Hit:* 32 (4d10 + 10) slashing damage plus 18 (4d8) fire damage.

**Lava Ball.** Ranged Weapon Attack: +18 to hit, range 120/480 ft., one target. *Hit:* 29 (3d12 + 10) bludgeoning damage plus 10 (3d6) fire damage, and the target must succeed on a DC 26 Strength saving throw or have the prone condition.

**Slam.** Melee Weapon Attack: +18 to hit, reach 20 ft., one target. *Hit:* 28 (4d8 + 10) force damage.

**Lava Wave (Recharge 5–6).** The scion emits a wave of lava from its blade, hands, or mouth in a 90-foot cone. Each creature in that area must make a DC 25 Dexterity saving throw. On a failed save, a creature takes 60 (11d10) fire damage and has the restrained condition from being embedded in hardening rock. A creature can make a DC 25 Strength (Athletics) check as an action, freeing itself or a creature within reach from the rock on a success. The rock has AC 17 and 40 hit points, and it is immune to fire, poison, and psychic damage. On a successful save, a creature takes half as much damage only.


---

### Bonus Actions

**Earth-Shaking Movement.** The scion moves up to its speed and then sends a shock wave through the ground in a 60-foot-radius circle centered on itself. Each creature on the ground in that area that is concentrating must succeed on a DC 26 Constitution saving throw or lose concentration.

**Incendiary Smoke.** The scion causes smoke and white-hot embers to billow from its skin, filling a 30-foot-radius sphere centered on itself that moves with it. While the scion's skin billows smoke, ranged attacks against the scion are made with disadvantage. A creature that moves into the smoke for the first time on a turn or starts its turn there must succeed on a DC 25 Constitution saving throw or take 14 (4d6) fire damage. The scion's skin stops billowing smoke after 1 minute, when the scion dies, or when the scion uses this bonus action to stop the smoke.


---

> [!column|flex 3]
>> [!important]- QUESTS:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Compendium/Party/Quests")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORY
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Session Notes")
>>         - file.hasLink(this.file)
>> ```