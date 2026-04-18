---
type: pc
race: "Dragon"
class:
 - "Deep Dragon Wyrmling"
subClass:
 - "CR 1"
cover: "Deep Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/dragon
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/1
  - source/ftd
---
###### Deep Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Deep Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Dragon |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Dragon |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 11 | 12 | 11 | 12 | 13 |
| **Mod** | +2 | +0 | +1 | +0 | +1 | +1 |

**Speed:** 30 ft., burrow 15 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 90 ft., passive Perception 13
**Languages:** Draconic
**Saving Throws:** Dex +2, Con +3, Wis +3, Cha +3
**Skills:** Perception +3, Persuasion +3, Stealth +4
**Damage Resistances:** poison; psychic
**Condition Immunities:** charmed; frightened; poisoned

---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage.

**Nightmare Breath (Recharge 5–6).** The dragon exhales a cloud of spores in a 15-foot cone. Each creature in that area must make a DC 11 Wisdom saving throw. On a failed save, the creature takes 5 (1d10) psychic damage, and it is frightened of the dragon for 1 minute. On a successful save, the creature takes half as much damage with no additional effects. A frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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