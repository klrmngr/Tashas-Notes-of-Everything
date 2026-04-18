---
type: pc
race: "Humanoid"
class:
 - "Transcendent Order Instinct"
subClass:
 - "CR 3"
cover: "Transcendent Order Instinct.png"
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
###### Transcendent Order Instinct
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Transcendent Order Instinct.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 16 (Unarmored Defense) |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 16 | 12 | 10 | 16 | 12 |
| **Mod** | +0 | +3 | +1 | +0 | +3 | +1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus one more language
**Saving Throws:** Wis +5, Cha +3
**Skills:** Acrobatics +5, Perception +5, Performance +3

---

### Traits

**Unarmored Defense.** While the instinct is wearing no armor and wielding no shield, its AC includes its Wisdom modifier.


---

### Actions

**Multiattack.** The instinct makes three Unarmed Strike attacks.

**Unarmed Strike.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage.


---

### Reactions

**Deflect Blow.** In response to being hit by a melee attack roll, the instinct partially deflects the blow. The damage the instinct takes from the attack is reduced by 1d6.


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