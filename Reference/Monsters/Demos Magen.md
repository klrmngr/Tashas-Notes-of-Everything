---
type: pc
race: "Construct"
class:
 - "Demos Magen"
subClass:
 - "CR 2"
cover: "Demos Magen.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/2
  - source/idrotf
---
###### Demos Magen
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Demos Magen.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (chain mail) |
> | :FasHeart: HP | 51 (6d8 + 24) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 14 | 18 | 10 | 10 | 7 |
| **Mod** | +2 | +2 | +4 | +0 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** understands the languages of its creator but can't speak
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; frightened; paralyzed; poisoned

---

### Traits

**Fiery End.** If the magen dies, its body disintegrates in a harmless burst of fire and smoke, leaving behind anything it was wearing or carrying.

**Magic Resistance.** The magen has advantage on saving throws against spells and other magical effects.

**Unusual Nature.** The magen doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The magen makes two melee attacks.

**Greatsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 9 (2d6 + 2) slashing damage.

**Light Crossbow.** Ranged Weapon Attack: +4 to hit, range 80/320 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.


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