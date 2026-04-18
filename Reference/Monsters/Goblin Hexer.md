---
type: pc
race: "Fey (goblinoid)"
class:
 - "Goblin Hexer"
subClass:
 - "CR 3"
cover: "Goblin Hexer.png"
campaign:
locations:
tags:
  - race/goblinoid
  - affinity/hostile
  - type/fey
  - size/small
  - cr/3
  - source/xmm
---
###### Goblin Hexer
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Goblin Hexer.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Fey (goblinoid) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 45 (10d6 + 10) |
> | :FasUserGroup: Race | Fey (goblinoid) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 16 | 12 | 16 | 10 | 10 |
| **Mod** | -1 | +3 | +1 | +3 | +0 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common, Goblin
**Skills:** Sleight Of Hand +5, Stealth +7

---

### Actions

**Multiattack.** The goblin makes two Hex Stick attacks. It can replace one attack with a use of Spellcasting.

**Hex Stick.** m,r +5, reach 5 ft. or range 60 ft. *Hit:* 12 (2d8 + 3) Psychic damage.


---

### Reactions

**Jinx.**  A creature the goblin can see hits it with an attack roll. dwis DC 13, the triggering creature.  The attack misses instead.


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