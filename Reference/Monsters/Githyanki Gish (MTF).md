---
type: pc
race: "Humanoid (gith)"
class:
 - "Githyanki Gish"
subClass:
 - "CR 10"
cover: "Githyanki Gish.png"
campaign:
locations:
tags:
  - race/gith
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/10
  - source/mtf
---
###### Githyanki Gish
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Githyanki Gish.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gith) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (half plate armor) |
> | :FasHeart: HP | 123 (19d8 + 38) |
> | :FasUserGroup: Race | Humanoid (gith) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 17 | 15 | 14 | 16 | 15 | 16 |
| **Mod** | +3 | +2 | +2 | +3 | +2 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Gith
**Saving Throws:** Con +6, Int +7, Wis +6
**Skills:** Insight +6, Perception +6, Stealth +6

---

### Traits

**War Magic.** When the githyanki uses its action to cast a spell, it can make one weapon attack as a bonus action.


---

### Actions

**Multiattack.** The githyanki makes two longsword attacks.

**Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage plus 18 (4d8) psychic damage, or 8 (1d10 + 3) slashing damage plus 18 (4d8) psychic damage if used with two hands.


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