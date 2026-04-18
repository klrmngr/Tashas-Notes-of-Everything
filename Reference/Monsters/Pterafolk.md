---
type: pc
race: "Monstrosity"
class:
 - "Pterafolk"
subClass:
 - "CR 1"
cover: "Pterafolk.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/1
  - source/toa
---
###### Pterafolk
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Pterafolk.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 26 (4d10 + 4) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 13 | 12 | 9 | 10 | 11 |
| **Mod** | +2 | +1 | +1 | -1 | +0 | +0 |

**Speed:** 30 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** Common
**Skills:** Perception +2, Survival +2

---

### Traits

**Terror Dive.** If the pterafolk is flying and dives at least 30 feet straight toward a target, and then hits that target with a melee weapon attack, the target is frightened until the end of its next turn.


---

### Actions

**Multiattack.** The pterafolk makes three attacks: one with its bite and two with its claws. Alternatively, it makes two melee attacks with its javelin.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4 + 2) piercing damage.

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) slashing damage.

**Javelin.** Melee or Ranged Weapon Attack: +4 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 9 (2d6 + 2) piercing damage.


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