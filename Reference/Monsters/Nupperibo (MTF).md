---
type: pc
race: "Fiend (devil)"
class:
 - "Nupperibo"
subClass:
 - "CR 1/2"
cover: "Nupperibo.png"
campaign:
locations:
tags:
  - race/devil
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/1-2
  - source/mtf
---
###### Nupperibo
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Nupperibo.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Fiend (devil) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Fiend (devil) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 13 | 3 | 8 | 1 |
| **Mod** | +3 | +0 | +1 | -4 | -1 | -5 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 10 ft. (blind beyond this radius), passive Perception 11
**Languages:** understands Infernal but can't speak
**Skills:** Perception +1
**Damage Resistances:** acid; cold; bludgeoning, piercing, slashing from nonmagical attacks that aren't silvered
**Damage Immunities:** fire; poison
**Condition Immunities:** blinded; charmed; frightened; poisoned

---

### Traits

**Cloud of Vermin.** Any creature, other than a devil, that starts its turn within 20 feet of the nupperibo must make a DC 11 Constitution saving throw. A creature within the areas of two or more nupperibos makes the saving throw with disadvantage. On a failure, the creature takes 2 (1d4) piercing damage.

**Hunger-Driven.** In the Nine Hells, the nupperibos can flawlessly track any creature that has taken damage from any nupperibo's Cloud of Vermin within the previous 24 hours.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage.


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