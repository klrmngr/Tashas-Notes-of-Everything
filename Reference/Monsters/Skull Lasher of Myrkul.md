---
type: pc
race: "Humanoid (human)"
class:
 - "Skull Lasher of Myrkul"
subClass:
 - "CR 1"
cover: "Skull Lasher of Myrkul.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/bgdia
---
###### Skull Lasher of Myrkul
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Skull Lasher of Myrkul.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 15 | 16 | 13 | 10 |
| **Mod** | +0 | +2 | +2 | +3 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Abyssal, Common, Infernal
**Saving Throws:** Wis +3
**Skills:** Arcana +5, Religion +5

---

### Actions

**Multiattack.** The skull lasher makes two attacks with its flail.

**Iron Skull Flail.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) bludgeoning damage plus 7 (2d6) necrotic damage, and the target has disadvantage on all saving throws until the end of the skull lasher's next turn.

**Ray of Sickness (1st-Level Spell; Requires a Spell Slot).** Ranged Spell Attack: +5 to hit, range 60 ft., one creature. *Hit:* 9 (2d8) poison damage, and the target must succeed on a DC 13 Constitution saving throw or be poisoned until the end of the skull lasher's next turn. If the skull lasher casts this spell using a spell slot of 2nd level or higher, the damage increases by 1d8 for each slot level above 1st.


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