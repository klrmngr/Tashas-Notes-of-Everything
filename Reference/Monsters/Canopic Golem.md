---
type: pc
race: "Construct"
class:
 - "Canopic Golem"
subClass:
 - "CR 13"
cover: "Canopic Golem.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/13
  - source/cm
---
###### Canopic Golem
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Canopic Golem.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 13 (10,000 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 252 (24d10 + 120) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 10 | 20 | 7 | 11 | 1 |
| **Mod** | +5 | +0 | +5 | -2 | +0 | -5 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** —
**Saving Throws:** Int +3, Wis +5, Cha +0
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; paralyzed; petrified; poisoned

---

### Traits

**Limited Spell Immunity.** The golem automatically succeeds on saving throws against spells of 7th level or lower, and the attack rolls of such spells always miss it.

**Unusual Nature.** The golem doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The golem makes two attacks.

**Slam.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 27 (4d10 + 5) force damage.

**Crystal Dart.** Ranged Weapon Attack: +10 to hit, range 120 ft., one target. *Hit:* 14 (2d8 + 5) force damage.


---

### Reactions

**Spell Deflection.** In response to a spell attack missing the golem, it causes that spell to hit another creature within 120 feet of it that it can see.


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