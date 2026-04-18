---
type: pc
race: "Fiend (yugoloth)"
class:
 - "Canoloth"
subClass:
 - "CR 8"
cover: "Canoloth.png"
campaign:
locations:
tags:
  - race/yugoloth
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/8
  - source/mpmm
---
###### Canoloth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Canoloth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Medium Fiend (yugoloth) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 120 (16d8 + 48) |
> | :FasUserGroup: Race | Fiend (yugoloth) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 10 | 17 | 5 | 17 | 12 |
| **Mod** | +4 | +0 | +3 | -3 | +3 | +1 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 19
**Languages:** Abyssal, Infernal, telepathy 60 ft.
**Skills:** Investigation +3, Perception +9
**Damage Resistances:** cold; fire; lightning; bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** acid; poison
**Condition Immunities:** poisoned

---

### Traits

**Dimensional Lock.** Other creatures can't teleport to or from a space within 60 feet of the canoloth. Any attempt to do so is wasted.

**Magic Resistance.** The canoloth has advantage on saving throws against spells and other magical effects.

**Uncanny Senses.** The canoloth can't be surprised unless it's incapacitated.


---

### Actions

**Multiattack.** The canoloth makes one Bite or Tongue attack and one Claw attack.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage plus 18 (4d8) force damage.

**Claw.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage plus 9 (2d8) force damage.

**Tongue.** Melee Weapon Attack: +7 to hit, reach 30 ft., one target. *Hit:* 10 (1d12 + 4) piercing damage plus 7 (2d6) acid damage. If the target is Medium or smaller, it is grappled (escape DC 15), pulled up to 30 feet toward the canoloth, and restrained until the grapple ends. The canoloth can grapple one target at a time with its tongue.


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