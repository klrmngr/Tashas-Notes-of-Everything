---
type: pc
race: "Dragon (gem)"
class:
 - "Topaz Dragon Wyrmling"
subClass:
 - "CR 2"
cover: "Topaz Dragon Wyrmling.png"
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
###### Topaz Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Topaz Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Dragon (gem) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 12 | 13 | 14 | 13 | 14 |
| **Mod** | +2 | +1 | +1 | +2 | +1 | +2 |

**Speed:** 30 ft., fly 60 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 120 ft., passive Perception 15
**Languages:** Draconic
**Saving Throws:** Dex +3, Con +3, Wis +3, Cha +4
**Skills:** Intimidation +6, Perception +5, Stealth +3
**Damage Resistances:** cold; necrotic

---

### Traits

**Amphibious.** The dragon can breathe both air and water.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (1d10 + 2) piercing damage plus 2 (1d4) necrotic damage.

**Desiccating Breath (Recharge 5–6).** The dragon exhales yellowish necrotic energy in a 15-foot cone. Each creature in that area must make a DC 11 Constitution saving throw. On a failed save, the creature takes 21 (6d6) necrotic damage and is weakened until the end of its next turn. A weakened creature has disadvantage on Strength-based ability checks and Strength saving throws, and the creature's weapon attacks that rely on Strength deal half damage. On a successful save, the creature takes half as much damage and isn't weakened.


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