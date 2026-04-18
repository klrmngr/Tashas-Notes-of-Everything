---
type: pc
race: "Plant"
class:
 - "Needle Spawn"
subClass:
 - "CR 1/2"
cover: "Needle Spawn.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/medium
  - cr/1-2
  - source/mff
---
###### Needle Spawn
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MFF
___

> [!infobox|no-t right]
> ![[Needle Spawn.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Plant |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 16 (3d8 + 3) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | MFF |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 17 | 12 | 6 | 13 | 6 |
| **Mod** | +1 | +3 | +1 | -2 | +1 | -2 |

**Speed:** 30 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 11
**Languages:** Sylvan
**Skills:** Stealth +5
**Condition Immunities:** blinded; deafened; exhaustion

---

### Traits

**Close Quarters Shooting.** The needle spawn does not suffer disadvantage on ranged attacks while within 5 feet of a hostile creature that can see it and isn't incapacitated, if the target of the attack is also within 5 feet of the needle spawn.


---

### Actions

**Needle Volley.** The needle spawn makes up to 1d6 needle attacks, but it cannot attack the same target more than twice during its turn.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage.

**Needle.** Ranged Weapon Attack: +5 to hit, range 60 ft., one target. *Hit:* 5 (1d4 + 3) piercing damage.


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