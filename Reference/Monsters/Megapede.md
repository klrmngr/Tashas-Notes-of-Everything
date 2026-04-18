---
type: pc
race: "Monstrosity"
class:
 - "Megapede"
subClass:
 - "CR 11"
cover: "Megapede.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/11
  - source/bam
---
###### Megapede
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Megapede.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 175 (13d20 + 39) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 10 | 17 | 1 | 10 | 3 |
| **Mod** | +6 | +0 | +3 | -5 | +0 | -4 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 18
**Languages:** —
**Saving Throws:** Con +7, Wis +4
**Skills:** Perception +8, Stealth +4

---

### Actions

**Multiattack.** The megapede makes one Bite attack and uses either Life Drain or Psychic Bomb.

**Bite.** Melee Weapon Attack: +10 to hit, reach 20 ft., one target. *Hit:* 22 (3d10 + 6) piercing damage plus 22 (5d8) poison damage.

**Life Drain.** The megapede magically drains life energy from other creatures nearby. Each creature within 15 feet of the megapede must make a DC 15 Constitution saving throw, taking 16 (3d10) necrotic damage on a failed save, or half as much damage on a successful one.

**Psychic Bomb.** The megapede targets one creature it can see within 60 feet of itself. The target must make a DC 15 Wisdom saving throw. On a failed save, the target takes 22 (5d8) psychic damage and is incapacitated until the end of its next turn. On a successful save, the target takes half as much damage and isn't incapacitated.


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