---
type: pc
race: "Humanoid (human)"
class:
 - "Knight of Eldraine"
subClass:
 - "CR 3"
cover: "Knight of Eldraine.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/3
  - source/mcv4ec
---
###### Knight of Eldraine
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Knight of Eldraine.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 20 (plate, shield) |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 14 | 13 | 11 | 13 |
| **Mod** | +3 | +1 | +2 | +1 | +0 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common
**Saving Throws:** Con +4, Wis +2

---

### Traits

**Knightly Virtue.** The knight has one of the following traits, depending on the court it serves:
- **Courage (Embereth).** The knight has advantage on Wisdom checks and Wisdom saving throws.
- **Knowledge (Vantress).** The knight has advantage on Intelligence checks and Intelligence saving throws.
- **Loyalty (Ardenvale).** The knight has advantage on Charisma checks and Charisma saving throws.
- **Persistence (Locthwain).** The knight has advantage on Constitution saving throws.
- **Strength (Garenbrig).** The knight has advantage on Strength checks and Strength saving throws.


---

### Actions

**Lance.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 9 (1d12 + 3) piercing damage plus 9 (2d8) radiant damage.

**Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands, plus 9 (2d8) radiant damage.

**Heavy Crossbow.** Ranged Weapon Attack: +3 to hit, range 100/400 ft., one target. *Hit:* 6 (1d10 + 1) piercing damage plus 9 (2d8) radiant damage.


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