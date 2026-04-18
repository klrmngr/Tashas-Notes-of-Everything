---
type: pc
race: "Monstrosity"
class:
 - "Chitine"
subClass:
 - "CR 1/2"
cover: "Chitine.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/1-2
  - source/vgm
---
###### Chitine
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Chitine.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (hide armor) |
> | :FasHeart: HP | 18 (4d6 + 4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 10 | 10 | 7 |
| **Mod** | +0 | +2 | +1 | +0 | +0 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Undercommon
**Skills:** Athletics +4, Stealth +4

---

### Traits

**Fey Ancestry.** The chitine has advantage on saving throws against being charmed, and magic can't put the chitine to sleep.

**Sunlight Sensitivity.** While in sunlight, the chitine has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.

**Web Sense.** While in contact with a web, the chitine knows the exact location of any other creature in contact with the same web.

**Web Walker.** The chitine ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The chitine makes three attacks with its daggers.

**Dagger.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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