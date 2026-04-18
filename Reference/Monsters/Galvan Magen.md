---
type: pc
race: "Construct"
class:
 - "Galvan Magen"
subClass:
 - "CR 3"
cover: "Galvan Magen.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/3
  - source/idrotf
---
###### Galvan Magen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Galvan Magen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 68 (8d8 + 32) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 18 | 18 | 12 | 10 | 7 |
| **Mod** | +0 | +4 | +4 | +1 | +0 | -2 |

**Speed:** 30 ft., fly 30 ft. ((hover)) &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Immunities:** lightning; poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Fiery End.** If the magen dies, its body disintegrates in a harmless burst of fire and smoke, leaving behind anything it was wearing or carrying.

**Magic Resistance.** The magen has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The magen doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The magen makes two Shocking Touch attacks.

**Shocking Touch.** Melee Spell Attack: +6 to hit, reach 5 ft., one target (the magen has advantage on the attack roll if the target is wearing armor made of metal). *Hit:* 7 (1d6 + 4) lightning damage.

**Static Discharge (Recharge 5–6).** The magen discharges a lightning bolt in a 60-foot line that is 5 feet wide. Each creature in that line must make a DC 14 Dexterity saving throw (with disadvantage if the creature is wearing armor made of metal), taking 22 (4d10) lightning damage on a failed save, or half as much damage on a successful one.


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