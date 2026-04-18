---
type: pc
race: "Fiend"
class:
 - "Howler"
subClass:
 - "CR 8"
cover: "Howler.png"
campaign:
locations:
tags:
  - race/fiend
  - affinity/hostile
  - type/fiend
  - size/large
  - cr/8
  - source/mpmm
---
###### Howler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Howler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Fiend |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Fiend |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 16 | 15 | 5 | 14 | 6 |
| **Mod** | +3 | +3 | +2 | -3 | +2 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** understands Abyssal but can't speak
**Skills:** Perception +5
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** frightened

---

### Traits

**Pack Tactics.** A howler has advantage on attack rolls against a creature if at least one of the howler's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The howler makes two Rending Bite attacks.

**Rending Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage, plus 22 (4d10) psychic damage if the target is frightened. This attack ignores damage resistance.

**Mind-Breaking Howl (Recharge 4–6).** The howler emits a keening howl in a 60-foot cone. Each creature in that area must succeed on a DC 13 Wisdom saving throw or take 16 (3d10) psychic damage and be frightened until the end of the howler's next turn. While a creature is frightened in this way, its speed is halved, and it is incapacitated. A target that successfully saves is immune to the Mind-Breaking Howl of all howlers for the next 24 hours.


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