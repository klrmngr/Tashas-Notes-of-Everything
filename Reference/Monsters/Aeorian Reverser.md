---
type: pc
race: "Monstrosity"
class:
 - "Aeorian Reverser"
subClass:
 - "CR 8"
cover: "Aeorian Reverser.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/8
  - source/egw
---
###### Aeorian Reverser
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Aeorian Reverser.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 133 (14d10 + 56) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 16 | 18 | 6 | 14 | 8 |
| **Mod** | +5 | +3 | +4 | -2 | +2 | -1 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** understands Draconic but can't speak
**Saving Throws:** Wis +5, Cha +2
**Skills:** Perception +5, Stealth +6, Survival +5
**Damage Immunities:** necrotic; radiant

---

### Traits

**Magic Resistance.** The reverser has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The reverser makes three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +8 to hit, range 5 ft., one creature. *Hit:* 11 (1d12 + 5) piercing damage plus 6 (1d12) force damage.

**Claws.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage plus 7 (2d6) force damage.


---

### Reactions

**Reversal.** When a creature the reverser can see within 30 feet of it regains hit points, the reverser reduces the number of hit points regained to 0, and the reverser deals 13 (3d8) force damage to the creature.


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