---
type: pc
race: "Monstrosity"
class:
 - "Aranea"
subClass:
 - "CR 2"
cover: "Aranea.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/fraif
---
###### Aranea
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: FRAiF
___

> [!infobox|no-t right]
> ![[Aranea.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | FRAiF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 17 | 12 | 12 | 10 | 15 |
| **Mod** | +0 | +3 | +1 | +1 | +0 | +2 |

**Speed:** 30 ft., climb 30 ft. ((spider or hybrid form only)) &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Common
**Skills:** Perception +2, Stealth +5

---

### Traits

**Spider Climb (Hybrid or Spider Form Only).** The aranea can climb difficult surfaces, including along ceilings, without needing to make an ability check.

**Web Walker.** The aranea ignores movement restrictions caused by webs, and it knows the location of any other creature in contact with the same web.


---

### Actions

**Multiattack.** The aranea makes two attacks, using Bite, Slam, or Sling in any combination.

**Bite (Hybrid or Spider Form Only).** m +5, reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing damage plus 2 (1d4) Poison damage.

**Slam.** m +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Bludgeoning damage.

**Sling (Humanoid or Hybrid Form Only).** r +5, range 30/120 ft. *Hit:* 8 (2d4 + 3) Bludgeoning damage.


---

### Bonus Actions

**Shape-Shift.** The aranea shape-shifts into a humanoid form, into a humanoid-spider hybrid form, or back into its true spider form. Its game statistics are the same in each form, except where noted. Any equipment it is wearing or carrying isn't transformed.


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