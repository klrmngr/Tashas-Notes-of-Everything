---
type: pc
race: "Dragon (gem)"
class:
 - "Crystal Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Crystal Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/2
  - source/ftd
---
###### Crystal Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Crystal Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon (gem) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 12 | 14 | 14 | 13 | 15 |
| **Mod** | +2 | +1 | +2 | +2 | +1 | +2 |

**Speed:** 30 ft., burrow 15 ft., climb 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 60 ft., passive Perception 15
**Languages:** Draconic, telepathy 120 ft.
**Saving Throws:** Dex +3, Con +4, Wis +3, Cha +4
**Skills:** Perception +5, Stealth +5, Survival +3
**Damage Resistances:** cold; radiant

---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 10 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage plus 2 (1d4) radiant damage.

**Scintillating Breath (Recharge 5–6).** The dragon exhales a burst of brilliant radiance in a 15-foot cone. Each creature in that area must make a DC 12 Constitution saving throw, taking 18 (4d8) radiant damage on a failed save, or half as much damage on a successful one. The dragon then gains 5 temporary hit points by absorbing a portion of the radiant energy.


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