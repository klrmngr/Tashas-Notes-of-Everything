---
type: pc
race: "Humanoid"
class:
 - "Champion of Usamigaras"
subClass:
 - "CR 2"
cover: "Champion of Usamigaras.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/qftis
---
###### Champion of Usamigaras
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: QftIS
___

> [!infobox|no-t right]
> ![[Champion of Usamigaras.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 12; 15 with mage armor |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | QftIS |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 17 | 14 | 15 |
| **Mod** | +0 | +2 | +1 | +3 | +2 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Saving Throws:** Int +5, Cha +4
**Skills:** Arcana +5, Deception +6, Sleight Of Hand +4

---

### Actions

**Multiattack.** The champion makes two Arcane Burst attacks or makes one Arcane Burst attack and uses Spellcasting.

**Arcane Burst.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 120 ft., one target. *Hit:* 8 (1d10 + 3) force damage.


---

### Bonus Actions

**Aura of Deception (1/Day).** The champion emits an aura of ghostly illusions that fills a 10-foot-radius sphere centered on itself. While this aura is active, creatures have disadvantage on attack rolls against the champion and any of the champion's allies that are in the aura. The aura moves with the champion and lasts for 1 minute, until the champion has the incapacitated condition, or until the champion uses another bonus action to end the aura.


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