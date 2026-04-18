---
type: pc
race: "Aberration"
class:
 - "Vampiric Ixitxachitl Cleric"
subClass:
 - "CR 2"
cover: "Vampiric Ixitxachitl Cleric.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/2
  - source/oota
---
###### Vampiric Ixitxachitl Cleric
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Out of the Abyss
___

> [!infobox|no-t right]
> ![[Vampiric Ixitxachitl Cleric.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Out of the Abyss |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 18 | 13 | 12 | 13 | 7 |
| **Mod** | +2 | +4 | +1 | +1 | +1 | -2 |

**Speed:** 0 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Abyssal, Ixitxachitl

---

### Actions

**Vampiric Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage. The target must succeed on a DC 11 Constitution saving throw or its hit point maximum is reduced by an amount equal to the damage taken, and the ixitxachitl regains hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0.


---

### Reactions

**Barbed Tail.** When a creature provokes an opportunity attack from the ixitxachitl, the ixitxachitl can make the following attack instead of using its bite.
Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage.


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