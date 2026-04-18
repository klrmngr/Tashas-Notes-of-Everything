---
type: pc
race: "Aberration"
class:
 - "Star Spawn Grue"
subClass:
 - "CR 1/4"
cover: "Star Spawn Grue.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/1-4
  - source/mpmm
---
###### Star Spawn Grue
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Star Spawn Grue.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 17 (5d6) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 13 | 10 | 9 | 11 | 6 |
| **Mod** | -2 | +1 | +0 | -1 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Deep Speech
**Damage Immunities:** psychic

---

### Traits

**Aura of Shrieks.** Creatures within 20 feet of the grue that aren't Aberrations have disadvantage on saving throws, as well as on attack rolls against creatures other than a star spawn grue.


---

### Actions

**Confounding Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 6 (2d4 + 1) piercing damage, and the target must succeed on a DC 10 Wisdom saving throw or attack rolls against it have advantage until the start of the grue's next turn.


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