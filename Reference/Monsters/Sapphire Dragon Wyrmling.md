---
type: pc
race: "Dragon (gem)"
class:
 - "Sapphire Dragon Wyrmling"
subClass:
 - "CR 3"
cover: "Sapphire Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/3
  - source/ftd
---
###### Sapphire Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Sapphire Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Dragon (gem) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 14 | 16 | 14 | 13 | 14 |
| **Mod** | +3 | +2 | +3 | +2 | +1 | +2 |

**Speed:** 30 ft., burrow 15 ft., climb 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 15
**Languages:** Draconic, telepathy 120 ft.
**Saving Throws:** Dex +4, Con +5, Wis +3, Cha +4
**Skills:** History +4, Perception +5, Persuasion +6, Stealth +4
**Damage Resistances:** lightning; thunder
**Condition Immunities:** frightened

---

### Traits

**Spider Climb.** The dragon can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Tunneler.** The dragon can burrow through solid rock at half its burrowing speed and can leave a 5-foot-diameter tunnel in its wake.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage plus 3 (1d6) thunder damage.

**Debilitating Breath (Recharge 5–6).** The dragon exhales a pulse of high-pitched, nearly inaudible sound in a 15-foot cone. Each creature in that area must make a DC 13 Constitution saving throw. On a failed save, the creature takes 22 (4d10) thunder damage and is incapacitated until the end of its next turn. On a successful save, the creature takes half as much damage and isn't incapacitated.


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