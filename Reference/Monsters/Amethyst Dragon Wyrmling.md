---
type: pc
race: "Dragon (gem)"
class:
 - "Amethyst Dragon Wyrmling"
subClass:
 - "CR 4"
cover: "Amethyst Dragon Wyrmling.png"
campaign:
locations:
tags:
  - race/gem
  - affinity/hostile
  - type/dragon
  - size/medium
  - cr/4
  - source/ftd
---
###### Amethyst Dragon Wyrmling
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Amethyst Dragon Wyrmling.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Dragon (gem) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Dragon (gem) |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 16 | 13 | 17 |
| **Mod** | +4 | +0 | +3 | +3 | +1 | +3 |

**Speed:** 30 ft., fly 60 ft. ((hover)), swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft., darkvision 120 ft., passive Perception 15
**Languages:** Draconic, telepathy 120 ft.
**Saving Throws:** Dex +2, Con +5, Wis +3, Cha +5
**Skills:** Arcana +7, Perception +5, Persuasion +5, Stealth +2
**Damage Resistances:** force; psychic
**Condition Immunities:** frightened; prone

---

### Traits

**Amphibious.** The dragon can breathe both air and water.


---

### Actions

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage plus 4 (1d8) force damage.

**Singularity Breath (Recharge 5–6).** The dragon creates a shining bead of gravitational force in its mouth, then releases the energy in a 15-foot cone. Each creature in that area must make a DC 13 Strength saving throw. On a failed save, the creature takes 22 (5d8) force damage, and its speed becomes 0 until the start of the dragon's next turn. On a successful save, the creature takes half as much damage, and its speed isn't reduced.


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