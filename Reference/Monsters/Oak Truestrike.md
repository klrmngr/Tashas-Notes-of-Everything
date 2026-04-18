---
type: pc
race: "Humanoid (elf)"
class:
 - "Oak Truestrike"
subClass:
 - "CR 2"
cover: "Oak Truestrike.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/ai
---
###### Oak Truestrike
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Oak Truestrike.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good or Neutral Evil |
> | :FasShield: AC | 15 (studded leather) |
> | :FasHeart: HP | 32 (5d8 + 10) |
> | :FasUserGroup: Race | Humanoid (elf) |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 16 | 14 | 10 | 13 | 11 |
| **Mod** | +1 | +3 | +2 | +0 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 13
**Languages:** Common
**Skills:** Nature +4, Perception +3, Performance +2, Stealth +5, Survival +3

---

### Traits

**Fey Ancestry.** Oak has advantage on saving throws against being charmed, and magic can't put him to sleep.

**Keen Hearing and Sight.** Oak has advantage on Wisdom (Perception) checks that rely on hearing or sight.


---

### Actions

**Multiattack.** Oak makes three attacks with his hooked daggers or his hand crossbow.

**Hooked Dagger.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.

**Hand Crossbow.** Ranged Weapon Attack: +5 to hit, range 30/120 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


---

### Reactions

**Return the Favor (3/Day).** When Oak takes damage from a melee weapon attack, he can make a hooked dagger attack.


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