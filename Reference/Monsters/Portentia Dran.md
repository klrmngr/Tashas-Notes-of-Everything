---
type: pc
race: "Monstrosity (shapechanger)"
class:
 - "Portentia Dran"
subClass:
 - "CR 3"
cover: "Portentia Dran.png"
campaign:
locations:
tags:
  - race/shapechanger
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/3
  - source/ai
---
###### Portentia Dran
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Portentia Dran.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Monstrosity (shapechanger) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (chain shirt) |
> | :FasHeart: HP | 45 (6d8 + 18) |
> | :FasUserGroup: Race | Monstrosity (shapechanger) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 16 | 13 | 12 | 14 |
| **Mod** | +1 | +4 | +3 | +1 | +1 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish
**Skills:** Deception +6, Insight +3, Perception +3
**Condition Immunities:** charmed

---

### Traits

**Sneak Attack (1/Turn).** Portentia deals an extra 14 (4d6) damage when she hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of Portentia that isn't incapacitated and Portentia doesn't have disadvantage on the attack roll.


---

### Actions

**Multiattack.** Portentia makes three melee attacks.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.

**Change Shape.** Portentia magically polymorphs into a humanoid or beast that has a challenge rating equal to or less than her own, or back into her true form. Any equipment she is wearing or carrying is absorbed or borne by the new form (her choice). In a new form, Portentia retains her game statistics and ability to speak, but her AC, movement modes, Strength, Dexterity, and special senses are replaced by those of the new form, and she gains any statistics and capabilities (except class features, legendary actions, and lair actions) that the new form has but that she lacks.


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