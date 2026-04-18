---
type: pc
race: "Humanoid (half-dragon)"
class:
 - "Zindar"
subClass:
 - "CR 8"
cover: "Zindar.png"
campaign:
locations:
tags:
  - race/half-dragon
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/toa
---
###### Zindar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Zindar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (half-dragon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 110 (17d8 + 34) |
> | :FasUserGroup: Race | Humanoid (half-dragon) |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 10 | 14 | 16 | 15 | 18 |
| **Mod** | +2 | +0 | +2 | +3 | +2 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 12
**Languages:** Common, Draconic, Dwarvish, Primordial
**Saving Throws:** Con +5, Wis +5
**Skills:** Arcana +6, History +9, Insight +5, Investigation +9
**Damage Resistances:** fire

---

### Traits

**Dragon Wings.** As a bonus action on his turn, Zindar can sprout a pair of dragon wings from his back, gaining a flying speed of 30 feet until he dismisses them as a bonus action.


---

### Actions

**Quarterstaff.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage when used with two hands.

**Breath Weapon (Recharge 5–6).** Zindar uses one of the following options:

**Fire Breath.** Zindar exhales fire in a 15-foot cone. Each creature in that area must make a DC 15 Dexterity saving throw, taking 22 (4d10) fire damage on a failed save, or half as much damage on a successful one.

**Weakening Breath.** Zindar exhales gas in a 15-foot cone. Each creature in that area must succeed on a DC 15 Strength saving throw or have disadvantage on Strength-based attack rolls, Strength checks, and Strength saving throws for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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