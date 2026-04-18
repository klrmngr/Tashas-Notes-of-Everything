---
type: pc
race: "Monstrosity"
class:
 - "Theran Chimera"
subClass:
 - "CR 7"
cover: "Theran Chimera.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/7
  - source/mot
---
###### Theran Chimera
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Theran Chimera.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 95 (10d10 + 40) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 19 | 3 | 14 | 10 |
| **Mod** | +4 | +1 | +4 | -4 | +2 | +0 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** understands Draconic but can't speak
**Saving Throws:** Con +7, Wis +5
**Skills:** Perception +5

---

### Traits

**Spell Turning.** The chimera has advantage on a saving throw against any spell that targets only the chimera (not an area). If the chimera's saving throw is successful and the spell is of 4th level or lower, the spell has no effect on the chimera and instead targets the caster.


---

### Actions

**Multiattack.** The chimera makes three attacks: one with its claws, one with its head, and one with its tail. When its breath weapon is available, it can use the breath in place of its head or its claws.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage.

**Head.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 10 (1d12 + 4) piercing damage.

**Tail.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage.

**Breath Weapon (Recharge 5–6).** The chimera exhales fire in a 15-foot cone. Each creature in that area must make a DC 15 Dexterity saving throw, taking 32 (5d12) fire damage on a failed save, or half as much damage on a successful one.


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