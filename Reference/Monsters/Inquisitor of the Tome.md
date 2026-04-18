---
type: pc
race: "Humanoid"
class:
 - "Inquisitor of the Tome"
subClass:
 - "CR 8"
cover: "Inquisitor of the Tome.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/8
  - source/vrgr
---
###### Inquisitor of the Tome
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VRGR
___

> [!infobox|no-t right]
> ![[Inquisitor of the Tome.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Humanoid |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 77 (14d8 + 14) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | VRGR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 12 | 19 | 16 | 15 |
| **Mod** | +0 | +1 | +1 | +4 | +3 | +2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 30 ft., passive Perception 13
**Languages:** any four languages, telepathy 120 ft.
**Saving Throws:** Int +7, Wis +6, Cha +5
**Skills:** Arcana +10, History +7, Nature +7, Religion +10
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The inquisitor attacks twice.

**Force Bolt.** Ranged Spell Attack: +7 to hit, range 120 ft., one target. *Hit:* 22 (4d8 + 4) force damage, and if the target is a Large or smaller creature, the inquisitor can push it up to 10 feet away.

**Silver Longsword.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage, or 9 (1d10 + 4) if used with two hands, plus 18 (4d8) force damage.

**Implode (Recharge 4–6).** Each creature in a 20-foot-radius sphere centered on a point the inquisitor can see within 120 feet of it must succeed on a DC 15 Constitution saving throw or take 31 (6d8 + 4) force damage and be knocked prone and moved to the unoccupied space closest to the sphere's center. Large and smaller objects that aren't being worn or carried in the sphere automatically take the damage and are similarly moved.


---

### Reactions

**Telekinetic Deflection.** In response to being hit by an attack roll, the inquisitor increases its AC by 4 against the attack. If this causes the attack to miss, the attacker is hit by the attack instead.


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