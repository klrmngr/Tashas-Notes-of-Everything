---
type: pc
race: "Dragon"
class:
 - "Moonstone Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Moonstone Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/ftd
---
###### Moonstone Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Moonstone Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 16 | 14 | 17 |
| **Mod** | +3 | +2 | +2 | +3 | +2 | +3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Int +5, Wis +4, Cha +5
**Skills:** Perception +4, Persuasion +5, Stealth +4
**Condition Immunities:** charmed

---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage plus 3 (1d6) radiant damage.

**Breath Weapon (Recharge 5–6).** The dragon uses one of the following breath weapons:
- **Dream Breath.** The dragon exhales mist in a 90-foot cone. Each creature in that area must succeed on a DC 12 Constitution saving throw or fall unconscious for 10 minutes. This effect ends for a creature if the creature takes damage or someone uses an action to wake it.
- **Moonlight Breath.** The dragon exhales a beam of moonlight in a 30-foot line that is 5 feet wide. Each creature in that area must make a DC 12 Dexterity saving throw, taking 14 (4d6) radiant damage on a failed save, or half as much damage on a successful one.


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