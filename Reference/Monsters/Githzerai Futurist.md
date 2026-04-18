---
type: pc
race: "Aberration (gith)"
class:
 - "Githzerai Futurist"
subClass:
 - "CR 9"
cover: "Githzerai Futurist.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/9
  - source/mpp
---
###### Githzerai Futurist
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Githzerai Futurist.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Aberration (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (psychic defense) |
> | :FasHeart: HP | 149 (23d8 + 46) |
> | :FasUserGroup: Race | Aberration (gith) |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 17 | 15 | 17 | 17 | 13 |
| **Mod** | +2 | +3 | +2 | +3 | +3 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 30 ft., passive Perception 17
**Languages:** Common, Gith
**Saving Throws:** Str +6, Dex +7, Int +7, Wis +7
**Skills:** Arcana +7, Insight +7, Perception +7

---

### Traits

**Psychic Defense.** While the githzerai is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The githzerai makes three Unarmed Strike or Psychic Bolt attacks.

**Unarmed Strike.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) bludgeoning damage plus 11 (2d10) psychic damage.

**Psychic Bolt.** Ranged Spell Attack: +7 to hit, range 60 ft., one creature. *Hit:* 21 (4d8 + 3) psychic damage.


---

### Reactions

**Future Insight (3/Day).** When the githzerai or a creature it can see makes an attack roll, a saving throw, or an ability check, the githzerai can cause the roll to be made with advantage or disadvantage.


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