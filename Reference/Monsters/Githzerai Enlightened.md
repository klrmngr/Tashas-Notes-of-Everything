---
type: pc
race: "Humanoid (gith)"
class:
 - "Githzerai Enlightened"
subClass:
 - "CR 10"
cover: "Githzerai Enlightened.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/mpmm
---
###### Githzerai Enlightened
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Githzerai Enlightened.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (psychic defense) |
> | :FasHeart: HP | 112 (15d8 + 45) |
> | :FasUserGroup: Race | Humanoid (gith) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 19 | 16 | 17 | 19 | 13 |
| **Mod** | +2 | +4 | +3 | +3 | +4 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 18
**Languages:** Gith
**Saving Throws:** Str +6, Dex +8, Int +7, Wis +8
**Skills:** Arcana +7, Insight +8, Perception +8

---

### Traits

**Psychic Defense.** While the githzerai is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The githzerai makes three Unarmed Strike attacks.

**Unarmed Strike.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) bludgeoning damage plus 18 (4d8) psychic damage.

**Temporal Strike (Recharge 6).** Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. *Hit:* 13 (2d8 + 4) bludgeoning damage plus 52 (8d12) psychic damage. The target must succeed on a DC 16 Wisdom saving throw or move 1 round forward in time. A target moved forward in time vanishes for the duration. When the effect ends, the target reappears in the space it left or in an unoccupied space nearest to that space if it's occupied.


---

### Reactions

**Slow Fall.** When the githzerai falls, it reduces any falling damage it takes by 50.


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