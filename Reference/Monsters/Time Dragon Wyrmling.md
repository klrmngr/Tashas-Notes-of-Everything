---
type: pc
race: "Dragon"
class:
 - "Time Dragon Wyrmling"
subClass:
 - "CR 5"
cover: "Time Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/5
  - source/mpp
---
###### Time Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Time Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 17 | 13 | 17 |
| **Mod** | +4 | +0 | +3 | +3 | +1 | +3 |

**Speed:** 30 ft., climb 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 120 ft., passive Perception 17
**Languages:** Draconic plus any two languages
**Saving Throws:** Dex +3, Con +6, Wis +4, Cha +6
**Skills:** Arcana +6, History +9, Perception +7, Stealth +6

---

### Actions

**Multiattack.** The dragon makes three Rend attacks.

**Rend.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage plus 3 (1d6) force damage.

**Time Breath (Recharge 5–6).** The dragon exhales a wave of shimmering light in a 15-foot cone. Nonmagical objects and vegetation in that area that aren't being worn or carried crumble to dust. Each creature in that area must make a DC 14 Constitution saving throw. On a failed save, a creature takes 27 (6d8) force damage and is magically weakened as it is desynchronized from the time stream. While the creature is in this state, attack rolls against it have advantage. On a successful save, a creature takes half as much damage only. A weakened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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