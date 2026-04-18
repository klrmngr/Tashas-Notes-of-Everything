---
type: pc
race: "Fey (elf)"
class:
 - "Smiler the Defiler"
subClass:
 - "CR 7"
cover: "Smiler the Defiler.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/7
  - source/bgdia
---
###### Smiler the Defiler
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGDIA
___

> [!infobox|no-t right]
> ![[Smiler the Defiler.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Medium Fey (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 18 (+2 leather armor) |
> | :FasHeart: HP | 165 (22d8 + 66) |
> | :FasUserGroup: Race | Fey (elf) |
> | :FasBook: Source | BGDIA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 20 | 16 | 18 | 11 | 18 |
| **Mod** | +2 | +5 | +3 | +4 | +0 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Elvish, Sylvan
**Skills:** Deception +7, Persuasion +7
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Fey Step (Recharge 4–6).** As a bonus action, Smiler can teleport up to 30 feet to an unoccupied space that he can see or to the empty seat of his infernal war machine.

**Magic Resistance.** Smiler has advantage on saving throws against spells and other magical effects.

**Equipment.** Smiler wears +2 leather armor. He carries seven soul coins in a bag and a +1 shortsword


---

### Actions

**Multiattack.** Smiler makes two weapon attacks. He can cast a spell in place of one of these attacks.

**+1 Shortsword.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d6 + 6) piercing damage.


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