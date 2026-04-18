---
type: pc
race: "Humanoid (wizard)"
class:
 - "Scholarly Mastermind"
subClass:
 - "CR 5"
cover: "Scholarly Mastermind.png"
campaign:
locations:
tags:
  - race/wizard
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/5
  - source/crcotn
---
###### Scholarly Mastermind
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Scholarly Mastermind.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Small Humanoid (wizard) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 82 (15d8 + 15) |
> | :FasUserGroup: Race | Humanoid (wizard) |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 13 | 18 | 16 | 14 |
| **Mod** | +0 | +2 | +1 | +4 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Common plus three other languages
**Saving Throws:** Int +7, Wis +6
**Skills:** Arcana +7, History +7, Insight +6, Perception +6

---

### Actions

**Multiattack.** The mastermind makes two Arcane Shock or Dagger of the Poisoned Mind attacks.

**Arcane Shock.** Melee or Ranged Spell Attack: +7 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 26 (4d10 + 4) lightning damage. If the target is a creature, it can't take reactions until the start of its next turn.

**Dagger of the Poisoned Mind.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage plus 10 (3d6) psychic damage. If the target is a creature, it must succeed on a DC 15 Wisdom saving throw or be frightened until the end of its next turn.


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