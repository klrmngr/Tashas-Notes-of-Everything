---
type: pc
race: "Humanoid (human)"
class:
 - "Inspired"
subClass:
 - "CR 2"
cover: "Inspired.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/erlw
---
###### Inspired
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Inspired.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 40 (9d8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 10 | 16 | 10 | 16 |
| **Mod** | +0 | +2 | +0 | +3 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Quori
**Saving Throws:** Int +5, Wis +2
**Skills:** Deception +7, Insight +2, Persuasion +7
**Damage Resistances:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Dual Mind.** The Inspired has advantage on Wisdom saving throws.


---

### Actions

**Multiattack.** The Inspired makes two crysteel dagger attacks. It can replace one attack with vicious mockery.

**Crysteel Dagger.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 10 (3d6) force damage.

**Vicious Mockery (Cantrip).** The Inspired unleashes a string of insults laced with subtle enchantments at one creature it can see within 60 feet of it. If the target can hear the Inspired, the target must succeed on a DC 13 Wisdom saving throw or take 2 (1d4) psychic damage and have disadvantage on the next attack roll it makes before the end of its next turn.


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