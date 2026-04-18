---
type: pc
race: "Monstrosity"
class:
 - "Two-Headed Cerberus"
subClass:
 - "CR 2"
cover: "Two-Headed Cerberus.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/mot
---
###### Two-Headed Cerberus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mythic Odysseys of Theros
___

> [!infobox|no-t right]
> ![[Two-Headed Cerberus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Mythic Odysseys of Theros |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 14 | 14 | 3 | 13 | 6 |
| **Mod** | +2 | +2 | +2 | -4 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** —
**Skills:** Perception +5, Stealth +4
**Damage Immunities:** fire; necrotic
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; stunned

---

### Traits

**Aggressive.** As a bonus action, the cerberus can move up to its speed toward a hostile creature that it can see.

**Multiheaded.** The cerberus can't be surprised, and it has advantage on saving throws against being knocked unconscious.

**Pack Tactics.** The cerberus has advantage on an attack roll against a creature if at least one of the cerberus's allies is within 5 feet of the creature and the ally isn't incapacitated.


---

### Actions

**Multiattack.** The cerberus makes two bite attacks.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6 + 2) piercing damage plus 2 (1d4) fire damage.

**Breath Weapon (Recharge 5–6).** The cerberus exhales a 15-foot cone of molten rock. Each creature in the cone must make a DC 12 Dexterity saving throw, taking 10 (3d6) fire damage on a failed save, or half as much damage on a successful one. On a failed save, a creature is also restrained by the hardening rock. A creature can make a DC 12 Strength (Athletics) check as an action, freeing itself or a creature within reach from the rock on a success. The rock has AC 17 and 10 hit points, and it is immune to fire, poison, and psychic damage.


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