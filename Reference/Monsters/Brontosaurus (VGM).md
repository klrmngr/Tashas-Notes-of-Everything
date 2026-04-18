---
type: pc
race: "Beast"
class:
 - "Brontosaurus"
subClass:
 - "CR 5"
cover: "Brontosaurus.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/gargantuan
  - cr/5
  - source/vgm
---
###### Brontosaurus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Brontosaurus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Gargantuan Beast |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 121 (9d20 + 27) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 9 | 17 | 2 | 10 | 7 |
| **Mod** | +5 | -1 | +3 | -4 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Saving Throws:** Con +6

---

### Actions

**Stomp.** Melee Weapon Attack: +8 to hit, reach 20 ft., one target. *Hit:* 27 (5d8 + 5) bludgeoning damage, and the target must succeed on a DC 14 Strength saving throw or be knocked prone.

**Tail.** Melee Weapon Attack: +8 to hit, reach 20 ft., one target. *Hit:* 32 (6d8 + 5) bludgeoning damage.


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