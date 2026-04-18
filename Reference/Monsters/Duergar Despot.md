---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Duergar Despot"
subClass:
 - "CR 12"
cover: "Duergar Despot.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/12
  - source/mpmm
---
###### Duergar Despot
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Duergar Despot.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 21 (natural armor) |
> | :FasHeart: HP | 119 (14d8 + 56) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 5 | 19 | 15 | 14 | 13 |
| **Mod** | +5 | -3 | +4 | +2 | +2 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** Dwarvish, Undercommon
**Saving Throws:** Con +8, Wis +6
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Magic Resistance.** The duergar has advantage on saving throws against spells and other magical effects.

**Psychic Engine.** When the duergar suffers a critical hit or is reduced to 0 hit points, psychic energy erupts from its frame to deal 14 (4d6) psychic damage to each creature within 5 feet of it.

**Sunlight Sensitivity.** While in sunlight, the duergar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The duergar makes two Iron Fist attacks and two Stomping Foot attacks. After one of the attacks, the duergar can move up to its speed without provoking opportunity attacks. It can replace one of the attacks with a use of Flame Jet.

**Iron Fist.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 23 (4d8 + 5) bludgeoning damage. If the target is a Large or smaller creature, it must succeed on a DC 17 Strength saving throw or be pushed up to 30 feet away in a straight line and be knocked prone.

**Stomping Foot.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 10 (1d10 + 5) bludgeoning damage, or 21 (3d10 + 5) to a prone target.

**Flame Jet.** The duergar spews flames in a line 100 feet long and 5 feet wide. Each creature in the line must make a DC 16 Dexterity saving throw, taking 18 (4d8) fire damage on a failed save, or half as much damage on a successful one.


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