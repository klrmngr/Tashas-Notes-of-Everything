---
type: pc
race: "Elemental"
class:
 - "Fume Drake"
subClass:
 - "CR 1/4"
cover: "Fume Drake.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-4
  - source/dosi
---
###### Fume Drake
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: DoSI
___

> [!infobox|no-t right]
> ![[Fume Drake.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d6 + 5) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | DoSI |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 12 | 6 | 10 | 11 |
| **Mod** | -2 | +2 | +1 | -2 | +0 | +0 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Draconic, Ignan
**Damage Immunities:** fire; poison
**Condition Immunities:** poisoned

---

### Traits

**Death Burst.** When the fume drake dies, it explodes in a cloud of noxious fumes. Each creature within 5 feet of the fume drake must succeed on a DC 11 Constitution saving throw or take 4 (1d8) poison damage.

**Unusual Nature.** The fume drake doesn't require food, drink, or sleep.


---

### Actions

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) fire damage.

**Scalding Breath (Recharge 6).** The fume drake exhales a 15-foot cone of scalding steam. Each creature in that area must make a DC 11 Dexterity saving throw, taking 4 (1d8) fire damage on a failed save, or half as much damage on a successful one.


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