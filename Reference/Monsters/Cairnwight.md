---
type: pc
race: "Undead"
class:
 - "Cairnwight"
subClass:
 - "CR 9"
cover: "Cairnwight.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/9
  - source/bgg
---
###### Cairnwight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Cairnwight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 10 | 21 | 10 | 12 | 9 |
| **Mod** | +6 | +0 | +5 | +0 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Giant
**Saving Throws:** Con +9, Wis +5
**Skills:** Athletics +10, Perception +5, Stealth +8
**Condition Immunities:** charmed; exhaustion; frightened; petrified

---

### Actions

**Multiattack.** The cairnwight makes two Slam attacks or two Rock attacks, and it uses its Petrifying Touch if available.

**Slam.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 22 (3d10 + 6) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +10 to hit, range 60/240 ft., one target. *Hit:* 19 (3d8 + 6) bludgeoning damage, and the target must succeed on a DC 17 Strength saving throw or have the prone condition.

**Petrifying Touch (Recharge 5–6).** The cairnwight touches one creature it can see within 10 feet of itself. The target must succeed on a DC 17 Constitution saving throw or take 26 (4d12) force damage and have the restrained condition as it begins to turn to stone. The affected target must repeat the saving throw at the end of its next turn. On a successful save, the effect ends on the target. On a failed save, the target has the petrified condition instead of the restrained condition.


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