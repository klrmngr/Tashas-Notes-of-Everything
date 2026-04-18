---
type: pc
race: "Giant"
class:
 - "Bloodfray Giant"
subClass:
 - "CR 6"
cover: "Bloodfray Giant.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/6
  - source/ggr
---
###### Bloodfray Giant
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Bloodfray Giant.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 103 (9d12 + 45) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 9 | 20 | 7 | 8 | 9 |
| **Mod** | +6 | -1 | +5 | -2 | -1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Giant
**Saving Throws:** Str +9, Con +8, Wis +2
**Skills:** Athletics +9, Perception +2

---

### Actions

**Chain.** Melee Weapon Attack: +9 to hit, reach 20 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage. If the target is a creature, it is grappled (escape DC 17). Until the grapple ends, the target is restrained, and the giant can't use this attack on anyone else.

**Rock.** Ranged Weapon Attack: +9 to hit, range 60/240 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage.


---

### Reactions

**Furious Defense.** After a creature the giant can see is dealt damage by a foe within 20 feet of the giant, the giant makes a chain attack against that foe.


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