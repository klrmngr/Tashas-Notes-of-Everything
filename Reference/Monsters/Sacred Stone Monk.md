---
type: pc
race: "Humanoid (human)"
class:
 - "Sacred Stone Monk"
subClass:
 - "CR 1/2"
cover: "Sacred Stone Monk.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/pota
---
###### Sacred Stone Monk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Sacred Stone Monk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 15 | 12 | 10 | 14 | 9 |
| **Mod** | +1 | +2 | +1 | +0 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** tremorsense 10 ft., passive Perception 14
**Languages:** Common
**Skills:** Acrobatics +4, Athletics +3, Perception +4

---

### Traits

**Unarmored Defense.** While the monk is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.

**Unarmored Movement.** While the monk is wearing no armor and wielding no shield, its walking speed increases by 10 feet (included in its speed).


---

### Actions

**Multiattack.** The monk makes two melee attacks.

**Unarmed Strike.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) bludgeoning damage.


---

### Reactions

**Parry.** The monk adds 2 to its AC against one melee or ranged weapon attack that would hit it. To do so, the monk must see the attacker.


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