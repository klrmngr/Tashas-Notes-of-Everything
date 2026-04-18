---
type: pc
race: "Elemental"
class:
 - "Galeb Duhr"
subClass:
 - "CR 6"
cover: "Galeb Duhr.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/medium
  - cr/6
  - source/mm
---
###### Galeb Duhr
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Galeb Duhr.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Elemental |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 85 (9d8 + 45) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 20 | 11 | 12 | 11 |
| **Mod** | +5 | +2 | +5 | +0 | +1 | +0 |

**Speed:** 15 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., tremorsense 60 ft., passive Perception 11
**Languages:** Terran
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; paralyzed; petrified; poisoned

---

### Traits

**False Appearance.** While the galeb duhr remains motionless, it is indistinguishable from a normal boulder.

**Rolling Charge.** If the galeb duhr rolls at least 20 feet straight toward a target and then hits it with a slam attack on the same turn, the target takes an extra 7 (2d6) bludgeoning damage. If the target is a creature, it must succeed on a DC 16 Strength saving throw or be knocked prone.


---

### Actions

**Slam.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) bludgeoning damage.

**Animate Boulders (1/Day).** The galeb duhr magically animates up to two boulders it can see within 60 feet of it. A boulder has statistics like those of a galeb duhr, except it has Intelligence 1 and Charisma 1, it can't be charmed or frightened, and it lacks this action option. A boulder remains animated as long as the galeb duhr maintains concentration, up to 1 minute (as if concentrating on a spell).


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