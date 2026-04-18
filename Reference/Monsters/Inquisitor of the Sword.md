---
type: pc
race: "Humanoid"
class:
 - "Inquisitor of the Sword"
subClass:
 - "CR 8"
cover: "Inquisitor of the Sword.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/vrgr
---
###### Inquisitor of the Sword
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Inquisitor of the Sword.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 91 (14d8 + 28) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 14 | 15 | 18 | 16 |
| **Mod** | +1 | +2 | +2 | +2 | +4 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 30 ft., passive Perception 17
**Languages:** any two languages, telepathy 120 ft.
**Saving Throws:** Int +5, Wis +7, Cha +6
**Skills:** Acrobatics +5, Athletics +4, Insight +7, Perception +7
**Condition Immunities:** charmed; frightened

---

### Traits

**Metabolic Control.** At the start of each of its turns, the inquisitor regains 10 hit points and can end one condition on itself, provided the inquisitor has at least 1 hit point.


---

### Actions

**Multiattack.** The inquisitor attacks twice with its Silver Longsword. After it hits or misses with an attack, the inquisitor can teleport up to 30 feet to an unoccupied space it can see.

**Silver Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) if used with two hands, plus 18 (4d8) force damage.


---

### Bonus Actions

**Blink Step.** The inquisitor teleports up to 60 feet to an unoccupied space it can see.


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