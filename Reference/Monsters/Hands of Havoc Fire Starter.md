---
type: pc
race: "Humanoid"
class:
 - "Hands of Havoc Fire Starter"
subClass:
 - "CR 4"
cover: "Hands of Havoc Fire Starter.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/4
  - source/mpp
---
###### Hands of Havoc Fire Starter
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Hands of Havoc Fire Starter.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (breastplate) |
> | :FasHeart: HP | 65 (10d8 + 20) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 14 | 10 | 16 | 11 |
| **Mod** | +3 | +2 | +2 | +0 | +3 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common plus one more language
**Saving Throws:** Str +5, Con +4
**Damage Resistances:** fire

---

### Actions

**Multiattack.** The fire starter makes two Havoc Hammer or Havoc Flask attacks.

**Havoc Hammer.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage plus 9 (2d8) fire damage. If the target is a creature, magical flames cling to it, causing it to take 3 (1d6) fire damage at the start of each of its turns. Immediately after taking this damage on its turn, the target can make a DC 13 Dexterity saving throw, ending the effect on itself on a successful save.

**Havoc Flask.** Ranged Weapon Attack: +4 to hit, range 30/90 ft., one target. *Hit:* 13 (2d12) fire damage. If the target is a creature, magical flames cling to it, causing it to take 3 (1d6) fire damage at the start of each of its turns. Immediately after taking this damage on its turn, the target can make a DC 13 Dexterity saving throw, ending the effect on itself on a successful save.
After the fire starter throws the flask, roll a d6; on a 3 or lower, the fire starter has no more flasks to throw.


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