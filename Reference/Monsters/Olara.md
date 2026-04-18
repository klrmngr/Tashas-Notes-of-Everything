---
type: pc
race: "Humanoid"
class:
 - "Olara"
subClass:
 - "CR 1/2"
cover: "Olara.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/crcotn
---
###### Olara
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Critical Role: Call of the Netherdeep
___

> [!infobox|no-t right]
> ![[Olara.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Critical Role: Call of the Netherdeep |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 14 | 12 | 11 | 13 | 11 |
| **Mod** | +0 | +2 | +1 | +0 | +1 | +0 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Any one language (usually Common)
**Skills:** Nature +4, Perception +5, Stealth +6, Survival +5
**Damage Resistances:** cold

---

### Traits

**Amphibious.** Olara can breathe air and water.

**Fey Ancestry.** Olara has advantage on saving throws to end the charmed condition on herself, and magic can't put her to sleep.

**Keen Hearing and Sight.** The scout has advantage on Wisdom (Perception) checks that rely on hearing or sight.


---

### Actions

**Multiattack.** Olara makes two melee attacks or two ranged attacks.

**Shortsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage.

**Longbow.** Ranged Weapon Attack: +4 to hit, ranged 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


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