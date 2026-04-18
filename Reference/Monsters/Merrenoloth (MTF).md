---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Merrenoloth"
subClass:
 - "CR 3"
cover: "Merrenoloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/3
  - source/mtf
---
###### Merrenoloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Merrenoloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 17 | 10 | 17 | 14 | 11 |
| **Mod** | -1 | +3 | +0 | +3 | +2 | +0 |

**Speed:** 30 ft., swim 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 60 ft., darkvision 60 ft., passive Perception 14
**Languages:** Abyssal, Infernal, telepathy 60 ft.
**Saving Throws:** Dex +5, Int +5
**Skills:** History +5, Nature +5, Perception +4, Survival +4
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The merrenoloth has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The merrenoloth's weapon attacks are magical.

**Teleport.** As a bonus action, the merrenoloth magically teleports, along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied space it can see.


---

### Actions

**Multiattack.** The merrenoloth uses Fear Gaze once and makes one oar attack.

**Oar.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (2d4 + 3) slashing damage.

**Fear Gaze.** The merrenoloth targets one creature it can see within 60 feet of it. The target must succeed on a DC 13 Wisdom saving throw or become frightened for 1 minute. The frightened target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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