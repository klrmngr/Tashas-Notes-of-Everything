---
type: pc
race: "Construct"
class:
 - "Stone Cursed"
subClass:
 - "CR 1"
cover: "Stone Cursed.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/mtf
---
###### Stone Cursed
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Stone Cursed.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 19 (3d8 + 4) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 5 | 14 | 5 | 8 | 7 |
| **Mod** | +3 | -3 | +2 | -3 | -1 | -2 |

**Speed:** 10 ft. &nbsp;|&nbsp; **Senses:** passive Perception 9
**Languages:** the languages it knew in life
**Damage Vulnerabilities:** bludgeoning
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; petrified; poisoned

---

### Traits

**Cunning Opportunist.** The stone cursed has advantage on the attack rolls of opportunity attacks.

**False Appearance.** While the stone cursed remains motionless, it is indistinguishable from a normal statue.


---

### Actions

**Petrifying Claws.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) slashing damage, or 14 (2d10 + 3) slashing damage if the attack roll had advantage. If the target is a creature, it must succeed on a DC 12 Constitution saving throw, or it begins to turn to stone and is restrained until the end of its next turn, when it must repeat the saving throw. The effect ends if the second save is successful; otherwise the target is petrified for 24 hours.


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