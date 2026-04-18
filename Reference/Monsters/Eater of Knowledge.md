---
type: pc
race: "Aberration"
class:
 - "Eater of Knowledge"
subClass:
 - "CR 6"
cover: "Eater of Knowledge.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/6
  - source/mpp
---
###### Eater of Knowledge
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Eater of Knowledge.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 102 (12d10 + 36) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 17 | 18 | 16 | 15 |
| **Mod** | +4 | +0 | +3 | +4 | +3 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** telepathy 120 ft.
**Saving Throws:** Str +7, Int +7
**Skills:** Arcana +7, Perception +6
**Damage Immunities:** psychic
**Condition Immunities:** charmed; frightened

---

### Traits

**Brains Devoured.** When the eater of knowledge is first encountered, roll 1d10 to determine the number of brains it has already consumed.

**Magic Resistance.** The eater of knowledge has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The eater of knowledge makes two Slam attacks. If both attacks hit the same creature and the target is Large or smaller, it has the grappled condition (escape DC 14) and must succeed on a DC 15 Intelligence saving throw or have the stunned condition until the grapple ends.

**Slam.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Extract Brain.** Melee Weapon Attack: +7 to hit, reach 5 ft., one Humanoid with the incapacitated condition. *Hit:* 45 (10d8) piercing damage. If this damage reduces the target to 0 hit points, the eater of knowledge kills the target by extracting and consuming its brain.


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