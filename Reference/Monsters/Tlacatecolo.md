---
type: pc
race: "Fiend (demon)"
class:
 - "Tlacatecolo"
subClass:
 - "CR 5"
cover: "Tlacatecolo.png"
campaign:
locations:
tags:
  - race/demon
  - affinity/hostile
  - type/fiend
  - size/medium
  - cr/5
  - source/jttrc
---
###### Tlacatecolo
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: JttRC
___

> [!infobox|no-t right]
> ![[Tlacatecolo.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Fiend (demon) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 78 (12d8 + 24) |
> | :FasUserGroup: Race | Fiend (demon) |
> | :FasBook: Source | JttRC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 17 | 14 | 10 | 15 | 10 |
| **Mod** | +1 | +3 | +2 | +0 | +2 | +0 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Abyssal, Common
**Saving Throws:** Dex +6, Con +5
**Skills:** Perception +5, Stealth +6
**Damage Resistances:** cold; poison
**Condition Immunities:** poisoned

---

### Traits

**Magic Resistance.** The tlacatecolo has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The tlacatecolo makes two Talon attacks.

**Talon.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 3) piercing damage plus 14 (3d8) poison damage.

**Change Shape.** The tlacatecolo magically transforms into a Medium owl, while retaining its game statistics (other than its size). This transformation ends if the tlacatecolo is reduced to 0 hit points or if it uses its action to end it.

**Plague Winds (Fiend Form Only; Recharge 5-6).** The tlacatecolo emits a chilling, disease-ridden wind in a 60-foot line that is 10 feet wide. Each creature in that area must succeed on a DC 13 Constitution saving throw or take 26 (4d12) cold damage and become poisoned.
While poisoned in this way, the creature can't regain hit points. At the end of every hour, the creature must succeed on a DC 13 Constitution saving throw or gain 1 level of exhaustion. If the creature is in direct sunlight when it makes this saving throw, it automatically succeeds on the save.
If the creature is targeted by magic that ends a poison or disease, such as lesser restoration, while the creature isn't in direct sunlight, the effect does not end.


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