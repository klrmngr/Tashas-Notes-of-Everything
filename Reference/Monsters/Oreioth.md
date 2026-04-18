---
type: pc
race: "Humanoid (human)"
class:
 - "Oreioth"
subClass:
 - "CR 2"
cover: "Oreioth.png"
campaign:
locations:
tags:
  - race/human
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/pota
---
###### Oreioth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Princes of the Apocalypse
___

> [!infobox|no-t right]
> ![[Oreioth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (human) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 11; 14 with mage armor |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (human) |
> | :FasBook: Source | Princes of the Apocalypse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 13 | 14 | 16 | 9 | 11 |
| **Mod** | -1 | +1 | +2 | +3 | -1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** Abyssal, Common
**Saving Throws:** Wis +1
**Skills:** Arcana +5, Investigation +5, Medicine +1

---

### Traits

**Grim Harvest.** Once per turn when Oreioth kills one or more creatures with a spell of 1st level or higher, he regains hit points equal to twice the spell's level.

**Swift Animation (Recharges after a Long Rest).** When a living Medium or Small humanoid within 30 feet of Oreioth dies, he can use an action on his next turn to cast animate dead on that humanoid's corpse, instead of using the spell's normal casting time.


---

### Actions

**Dagger.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4 + 1) piercing damage.


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