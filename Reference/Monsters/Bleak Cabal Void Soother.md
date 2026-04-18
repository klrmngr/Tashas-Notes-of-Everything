---
type: pc
race: "Humanoid"
class:
 - "Bleak Cabal Void Soother"
subClass:
 - "CR 3"
cover: "Bleak Cabal Void Soother.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/3
  - source/mpp
---
###### Bleak Cabal Void Soother
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Bleak Cabal Void Soother.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 55 (10d8 + 10) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 12 | 12 | 15 | 10 |
| **Mod** | +3 | +2 | +1 | +1 | +2 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common plus one more language
**Saving Throws:** Con +3, Wis +4
**Skills:** Medicine +4

---

### Actions

**Multiattack.** The void soother makes two Mace or Void Bolt attacks.

**Mace.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) bludgeoning damage plus 3 (1d6) force damage.

**Void Bolt.** Ranged Spell Attack: +4 to hit, range 90 ft., one target. *Hit:* 9 (2d8) force damage.


---

### Bonus Actions

**Soothing Word (3/Day).** The void soother speaks a magical word of mercy, healing one creature it can see within 60 feet of itself. The target regains 4 (1d4 + 2) hit points.


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