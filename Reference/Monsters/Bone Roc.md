---
type: pc
race: "Undead"
class:
 - "Bone Roc"
subClass:
 - "CR 8"
cover: "Bone Roc.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/8
  - source/veor
---
###### Bone Roc
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: VEoR
___

> [!infobox|no-t right]
> ![[Bone Roc.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 133 (14d12 + 42) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | VEoR |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 20 | 16 | 2 | 17 | 10 |
| **Mod** | +4 | +5 | +3 | -4 | +3 | +0 |

**Speed:** 15 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 16
**Languages:** —
**Saving Throws:** Dex +8, Wis +6
**Skills:** Perception +6
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Actions

**Multiattack.** The bone roc makes one Beak attack and two Talons attacks.

**Beak.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage.

**Talons.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 12 (2d6 + 5) slashing damage plus 10 (3d6) necrotic damage.


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