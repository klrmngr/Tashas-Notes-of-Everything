---
type: pc
race: "Undead"
class:
 - "Skeletal Juggernaut"
subClass:
 - "CR 5"
cover: "Skeletal Juggernaut.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/5
  - source/gos
---
###### Skeletal Juggernaut
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Skeletal Juggernaut.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 13 (armor scraps) |
> | :FasHeart: HP | 142 (19d10 + 38) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 15 | 6 | 8 | 5 |
| **Mod** | +3 | +2 | +2 | -2 | -1 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 9
**Languages:** —
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Disassemble.** If the juggernaut is reduced to 0 hit points, twelve skeletons rise from its remains.

**Falling Apart.** If the juggernaut does not have all of its hit points at the start of its turn, it loses 10 hit points.


---

### Actions

**Multiattack.** The juggernaut makes two claws attacks.

**Claws.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 12 (2d8 + 3) slashing damage.

**Avalanche of Bones (Recharge 5–6).** The juggernaut collapses into a large heap before quickly reforming. Each creature within 10 feet of the juggernaut must make a DC 14 Dexterity saving throw, taking 18 (4d8) bludgeoning damage on a failed save, or half as much damage on a successful one. A creature that fails this saving throw is also knocked prone.


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