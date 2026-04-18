---
type: pc
race: "Ooze"
class:
 - "Plasmoid Boss"
subClass:
 - "CR 4"
cover: "Plasmoid Boss.png"
campaign:
locations:
tags:
  - race/ooze
  - affinity/hostile
  - type/ooze
  - size/large
  - cr/4
  - source/bam
---
###### Plasmoid Boss
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Plasmoid Boss.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Ooze |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 82 (11d10 + 22) |
> | :FasUserGroup: Race | Ooze |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 14 | 14 | 13 | 15 |
| **Mod** | +4 | +1 | +2 | +2 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common
**Saving Throws:** Con +4, Wis +3
**Skills:** Deception +4, Intimidation +4, Persuasion +4
**Damage Resistances:** acid; poison

---

### Traits

**Amorphous.** The plasmoid can squeeze through a space as narrow as 1 inch wide, provided it is wearing and carrying nothing. It has advantage on ability checks it makes to initiate or escape a grapple.

**Hold Breath.** The plasmoid can hold its breath for 1 hour.


---

### Actions

**Multiattack.** The plasmoid makes three Pseudopod attacks.

**Pseudopod.** Melee Weapon Attack: +6 to hit (with advantage if the plasmoid has one or more allies within 10 feet of itself), reach 10 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.


---

### Reactions

**Uncanny Dodge.** The plasmoid halves the damage that it takes from an attack that hits it. The plasmoid must be able to see the attacker.


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