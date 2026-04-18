---
type: pc
race: "Humanoid (human)"
class:
 - "Don-Jon Raskin"
subClass:
 - "CR 1/2"
cover: "Don-Jon Raskin.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1-2
  - source/dip
---
###### Don-Jon Raskin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DIP
___

> [!infobox|no-t right]
> ![[Don-Jon Raskin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 44 (8d8 + 8) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | DIP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 10 | 13 | 12 | 10 | 14 |
| **Mod** | +0 | +0 | +1 | +1 | +0 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** Common, Dwarvish
**Saving Throws:** Dex +2, Con +3
**Skills:** Deception +4, Persuasion +4

---

### Traits

**Brave.** Don-Jon has advantage on saving throws against being frightened.

**Not Dead Yet (Recharges after a Long Rest).** If damage reduces Don-Jon to 0 hit points, he drops to 1 hit point instead and gains advantage on attack rolls until the end of his next turn.


---

### Actions

**Multiattack.** Don-Jon makes three melee attacks.

**Dagger.** Melee or Ranged Weapon Attack: +2 to hit, reach 5 ft. or range 20/60 ft., one target. *Hit:* 2 (1d4) piercing damage.

**Sling.** Ranged Weapon Attack: +2 to hit, range 30/120 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.


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