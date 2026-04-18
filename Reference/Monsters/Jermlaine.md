---
type: pc
race: "Humanoid (jermlaine)"
class:
 - "Jermlaine"
subClass:
 - "CR 1/8"
cover: "Jermlaine.png"
campaign:
locations:
tags:
  - race/jermlaine
  - affinity/hostile
  - type/humanoid
  - size/tiny
  - cr/1-8
  - source/mff
---
###### Jermlaine
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Jermlaine.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Tiny Humanoid (jermlaine) |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 3 (1d4 + 1) |
> | :FasUserGroup: Race | Humanoid (jermlaine) |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 12 | 13 | 10 | 11 | 7 |
| **Mod** | -3 | +1 | +1 | +0 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 30 ft., passive Perception 10
**Languages:** Undercommon
**Skills:** Stealth +5

---

### Traits

**Lurkers in Shadow.** Jermlaine are invisible to darkvision.

**Magic Resistance.** The jermlaine has advantage on saving throws against spells and other magical effects.

**Vermin Friend.** The jermlaine can speak to and understand rats and giant rats.

**Swarming Rush.** A jermlaine adds 1d4 to its weapon damage rolls while within 5 feet of another, conscious jermlaine.


---

### Actions

**Club.** Melee Weapon Attack: -1 to hit, reach 5 ft., one target. *Hit:* 1 (1d4 - 3) bludgeoning damage.

**Dart.** Ranged Weapon Attack: +3 to hit, range 20/60 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.


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