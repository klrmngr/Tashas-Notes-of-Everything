---
type: pc
race: "Dragon"
class:
 - "Silver Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Silver Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/mm
---
###### Silver Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Silver Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 12 | 11 | 15 |
| **Mod** | +4 | +0 | +3 | +1 | +0 | +2 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 14
**Languages:** Draconic
**Saving Throws:** Dex +2, Con +5, Wis +2, Cha +4
**Skills:** Perception +4, Stealth +2
**Damage Immunities:** cold

---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage.

**Breath Weapons (Recharge 5–6).** The dragon uses one of the following breath weapons.
- **Cold Breath.** The dragon exhales an icy blast in a 15-foot cone. Each creature in that area must make a DC 13 Constitution saving throw, taking 18 (4d8) cold damage on a failed save, or half as much damage on a successful one.
- **Paralyzing Breath.** The dragon exhales paralyzing gas in a 15-foot cone. Each creature in that area must succeed on a DC 13 Constitution saving throw or be paralyzed for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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