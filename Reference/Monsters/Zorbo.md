---
type: pc
race: "Monstrosity"
class:
 - "Zorbo"
subClass:
 - "CR 1/2"
cover: "Zorbo.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/1-2
  - source/toa
---
###### Zorbo
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tomb of Annihilation
___

> [!infobox|no-t right]
> ![[Zorbo.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 (see Natural Armor feature) |
> | :FasHeart: HP | 27 (6d6 + 6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Tomb of Annihilation |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 11 | 13 | 3 | 12 | 7 |
| **Mod** | +1 | +0 | +1 | -4 | +1 | -2 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** —
**Skills:** Athletics +3

---

### Traits

**Magic Resistance.** The zorbo has advantage on saving throws against spells and other magical effects.

**Natural Armor.** The zorbo magically absorbs the natural strength of its surroundings, adjusting its Armor Class based on the material it is standing or climbing on: AC 15 for wood or bone, AC 17 for earth or stone, or AC 19 for metal. If the zorbo isn't in contact with any of these substances, its AC is 10.


---

### Actions

**Destructive Claws.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 8 (2d6 + 1) slashing damage, and if the target is a creature wearing armor, carrying a shield, or in possession of a magic item that improves its AC, it must make a DC 11 Dexterity saving throw. On a failed save, one such item worn or carried by the creature (the target's choice) magically deteriorates, taking a permanent and cumulative −1 penalty to the AC it offers, and the zorbo gains a +1 bonus to AC until the start of its next turn. Armor reduced to an AC of 10 or a shield or magic item that drops to a 0 AC increase is destroyed.


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