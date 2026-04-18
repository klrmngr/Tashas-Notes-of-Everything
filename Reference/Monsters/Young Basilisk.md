---
type: pc
race: "Creature"
class:
 - "Young Basilisk"
subClass:
 - "CR 1"
cover: "Young Basilisk.png"
campaign:
locations:
tags:
  - race/creature
  - affinity/hostile
  - type/creature
  - size/small
  - cr/1
  - source/oota
---
###### Young Basilisk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Young Basilisk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Small Creature |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 22 (4d6 + 8) |
> | :FasUserGroup: Race | Creature |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 10 | 10 | 10 | 10 | 10 |
| **Mod** | +1 | +0 | +0 | +0 | +0 | +0 |

**Speed:** 15 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Petrifying Gaze.** If a creature starts its turn within 15 feet of the basilisk and the two of them can see each other, the basilisk can force the creature to make a DC 12 Constitution saving throw if the basilisk isn't incapacitated. On a failed save, the creature magically begins to turn to stone and is restrained. It must repeat the saving throw at the end of its next turn. On a success, the effect ends. On a failure, the creature is petrified until freed by the  greater restoration spell or other magic.
A creature that isn't surprised can avert its eyes to avoid the saving throw at the start of its turn. If it does so, it can't see the basilisk until the start of its next turn, when it can avert its eyes again. If it looks at the basilisk in the meantime, it must immediately make the save.
If the basilisk sees its reflection within 30 feet of it in bright light, it mistakes itself for a rival and targets itself with its gaze.


---

### Actions

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage plus 2 (1d4) poison damage.


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