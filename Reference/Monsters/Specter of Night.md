---
type: pc
race: "Undead"
class:
 - "Specter of Night"
subClass:
 - "CR 12"
cover: "Specter of Night.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/huge
  - cr/12
  - source/mcv4ec
---
###### Specter of Night
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Specter of Night.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Undead |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 142 (15d12 + 45) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 18 | 17 | 12 | 13 | 12 |
| **Mod** | +6 | +4 | +3 | +1 | +1 | +1 |

**Speed:** 60 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** understands Common but can't speak
**Saving Throws:** Dex +8, Wis +5
**Skills:** Perception +5
**Damage Resistances:** necrotic
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the specter fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The specter has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The specter uses Mournful Keening if available, then makes one Hooves attack and one Reaping Scythe attack.

**Hooves.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 16 (3d6 + 6) bludgeoning damage plus 28 (8d6) necrotic damage. If the target is a Medium or smaller creature, it must succeed on a DC 18 Strength saving throw or have the prone condition.

**Mournful Keening (Recharge 6).** The specter utters a keening wail, calling to those close to death. Each non-Undead creature within 120 feet of the specter must make a DC 15 Constitution saving throw. On a failure, the creature hears the wail and is marked for death.
A creature marked for death can't regain hit points, has disadvantage on death saving throws, and all attack rolls against it are made with advantage. This effect lasts for 1 minute or until the creature is targeted by a remove curse spell or similar magic.

**Reaping Scythe.** Melee Weapon Attack: +10 to hit, reach 10 ft., one target. *Hit:* 12 (1d12 + 6) slashing damage plus 28 (8d6) necrotic damage. If the target is a creature, it must succeed on a DC 15 Constitution saving throw or gain a level of exhaustion.


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