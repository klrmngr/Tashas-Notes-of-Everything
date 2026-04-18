---
type: pc
race: "Aberration"
class:
 - "Greater Star Spawn Emissary"
subClass:
 - "CR 21"
cover: "Greater Star Spawn Emissary.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/21
  - source/vrgr
---
###### Greater Star Spawn Emissary
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Greater Star Spawn Emissary.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 21 (33,000 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 290 (20d12 + 160) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 24 | 13 | 26 | 27 | 22 | 25 |
| **Mod** | +7 | +1 | +8 | +8 | +6 | +7 |

**Speed:** 40 ft., fly 40 ft. ((hover)) &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 23
**Languages:** all, telepathy 1,000 ft.
**Saving Throws:** Con +15, Int +15, Wis +13, Cha +14
**Skills:** Arcana +22, Perception +13
**Damage Resistances:** acid; force; necrotic; psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Legendary Resistance (4/Day).** If the emissary fails a saving throw, it can choose to succeed instead.

**Unusual Nature.** The emissary doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The emissary makes three attacks.

**Lashing Maw.** Melee Weapon Attack: +14 to hit, reach 15 ft., one target. *Hit:* 20 (2d10 + 7) piercing damage plus 13 (3d8) acid damage.

**Psychic Orb.** Ranged Spell Attack: +15 to hit, range 120 ft., one creature. *Hit:* 27 (3d12 + 8) psychic damage.

**Unearthly Bile (Recharge 5–6).** The emissary expels bile that splashes all creatures in a 30-foot-radius sphere centered on a point within 120 feet of the emissary. Each creature in that area must make a DC 23 Dexterity saving throw, taking 55 (10d10) acid damage on a failed save, or half as much damage on a successful one. For each creature that fails the saving throw, a gibbering mouther (see its entry in the Monster Manual) appears in an unoccupied space on a surface that can support it within 30 feet of that creature. The gibbering mouthers act right after the emissary on the same initiative count, gaining a +7 bonus to their attack and damage rolls, and fighting until they are destroyed. They disappear when the emissary dies.


---

### Legendary Actions

### 

**Attack.** The emissary teleports up to 30 feet to an unoccupied space it can see and makes one attack.

**Warp Space (Costs 2 Actions).** The emissary causes the ground in a 20-foot square that it can see within 90 feet of it to turn into teeth and maws until the start of its next turn. The area becomes 3 for the duration. Any creature takes 10 (3d6) piercing damage for each 5 feet it moves on this terrain.

**Mind Cloud (Costs 3 Actions).** The emissary unleashes a psychic wave. Each creature within 30 feet of the emissary must succeed on a DC 23 Wisdom saving throw or take 32 (5d12) psychic damage. In addition, every spell ends on creatures and objects of the emissary's choice in that area.


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