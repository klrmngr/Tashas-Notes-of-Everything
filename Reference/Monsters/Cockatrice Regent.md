---
type: pc
race: "Monstrosity"
class:
 - "Cockatrice Regent"
subClass:
 - "CR 8"
cover: "Cockatrice Regent.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/8
  - source/xmm
---
###### Cockatrice Regent
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Cockatrice Regent.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 136 (16d10 + 48) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 14 | 16 | 3 | 16 | 5 |
| **Mod** | +4 | +2 | +3 | -4 | +3 | -3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 13
**Languages:** —
**Saving Throws:** Wis +6
**Condition Immunities:** petrified

---

### Traits

**Flyby.** The cockatrice doesn't provoke an Opportunity Attack when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The cockatrice makes one Petrifying Bite attack and two Talons attacks.

**Petrifying Bite.** m +7, reach 5 ft. *Hit:* 13 (2d8 + 4) Piercing damage. If the target is a creature, it is subjected to the following effect. con DC 14. 1 The target has the Restrained condition and repeats the save at the end of its next turn if it is still Restrained, ending the effect on itself on a success. 2 The target has the Petrified condition instead of the Restrained condition.

**Talons.** m +7, reach 5 ft. *Hit:* 18 (4d6 + 4) Slashing damage.


---

### Reactions

**Magical Backlash.**  A creature within 120 feet of the cockatrice deals damage to it. ddex DC 14, the triggering creature.  13 (3d6 + 3) Force damage.


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