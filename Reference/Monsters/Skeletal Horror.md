---
type: pc
race: "Undead"
class:
 - "Skeletal Horror"
subClass:
 - "CR 6"
cover: "Skeletal Horror.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/6
  - source/aitfr-dn
---
###### Skeletal Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AitFR-DN
___

> [!infobox|no-t right]
> ![[Skeletal Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 150 (20d10 + 40) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | AitFR-DN |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 15 | 6 | 10 | 5 |
| **Mod** | +3 | +2 | +2 | -2 | +0 | -3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 16
**Languages:** —
**Skills:** Perception +3
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Actions

**Multiattack.** The horror makes two attacks with its claws.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 19 (3d10 + 3) slashing damage.

**Wave of Bones (Recharge 5–6).** The horror crashes into foes like a wave before quickly reforming. Each creature within 10 feet of the horror must make a DC 15 Dexterity saving throw, taking 18 (4d8) bludgeoning damage on a failed save, or half as much damage on a successful one. A creature that fails this saving throw is also knocked prone.


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