---
type: pc
race: "Undead (sorcerer)"
class:
 - "Skull Lord"
subClass:
 - "CR 15"
cover: "Skull Lord.png"
campaign:
locations:
tags:
  - race/sorcerer
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/15
  - source/mpmm
---
###### Skull Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Skull Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Medium Undead (sorcerer) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 18 (plate) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Undead (sorcerer) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 17 | 16 | 15 | 21 |
| **Mod** | +2 | +3 | +3 | +3 | +2 | +5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 22
**Languages:** all the languages it knew in life
**Skills:** Athletics +7, History +8, Perception +12, Stealth +8
**Damage Resistances:** cold; necrotic; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; poisoned; stunned; unconscious

---

### Traits

**Evasion.** If the skull lord is subjected to an effect that allows it to make a Dexterity saving throw to take only half the damage, the skull lord instead takes no damage if it succeeds on the saving throw and only half damage if it fails, provided it isn't incapacitated.

**Legendary Resistance (3/Day).** If the skull lord fails a saving throw, it can choose to succeed instead.

**Master of the Grave.** While within 30 feet of the skull lord, any Undead ally of the skull lord makes saving throws with advantage, and that ally regains 1d6 hit points whenever it starts its turn there.

**Unusual Nature.** The skull lord doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The skull lord makes three Bone Staff or Deathly Ray attacks.

**Bone Staff.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage plus 21 (6d6) necrotic damage.

**Deathly Ray.** Ranged Spell Attack: +10 to hit, range 60 ft., one target. *Hit:* 27 (5d8 + 5) necrotic damage.


---

### Legendary Actions

### 

**Attack.** The skull lord makes one Bone Staff or Deathly Ray attack.

**Move.** The skull lord moves up to its speed without provoking opportunity attacks.

**Summon Undead (Costs 2 Actions).** The skull lord summons up to five [[Skeleton|skeletons]] or [[Zombie|zombies]] in unoccupied spaces within 30 feet of it. They remain until destroyed. Undead summoned in this way roll initiative, act in the next available turn, and obey the skull lord. The skull lord can have no more than five Undead summoned by this ability at a time.


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