---
type: pc
race: "Monstrosity"
class:
 - "Underworld Cerberus"
subClass:
 - "CR 6"
cover: "Underworld Cerberus.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/6
  - source/mot
---
###### Underworld Cerberus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Underworld Cerberus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 104 (11d10 + 44) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 18 | 10 | 16 | 9 |
| **Mod** | +4 | +1 | +4 | +0 | +3 | -1 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** truesight 30 ft., passive Perception 19
**Languages:** understands all languages but can't speak
**Skills:** Athletics +7, Perception +9, Stealth +4
**Damage Immunities:** fire; necrotic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; stunned

---

### Traits

**Aggressive.** As a bonus action, the cerberus can move up to its speed toward a hostile creature that it can see.

**Multiheaded.** The cerberus can't be surprised, and it has advantage on saving throws against being knocked unconscious.

**Pack Tactics.** The cerberus has advantage on an attack roll against a creature if at least one of the cerberus's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The cerberus makes three bite attacks.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage plus 3 (1d6) fire damage.

**Breath Weapon (Recharge 5–6).** The cerberus exhales a 30-foot cone of molten rock. Each creature in the cone must make a DC 15 Dexterity saving throw, taking 21 (6d6) fire damage on a failed save, or half as much damage on a successful one. On a failed save, a creature is also restrained by the hardening rock. A creature can make a DC 15 Strength (Athletics) check as an action, freeing itself or a creature within reach from the rock on a success. The rock has AC 17 and 20 hit points, and it is immune to fire, poison, and psychic damage.


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