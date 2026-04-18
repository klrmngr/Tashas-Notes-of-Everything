---
type: pc
race: "Construct"
class:
 - "Living Lightning Bolt"
subClass:
 - "CR 5"
cover: "Living Lightning Bolt.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/5
  - source/erlw
---
###### Living Lightning Bolt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Living Lightning Bolt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 57 (6d10 + 24) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 18 | 3 | 10 | 6 |
| **Mod** | +0 | +2 | +4 | -4 | +0 | -2 |

**Speed:** 25 ft., fly 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** lightning
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; poisoned; prone

---

### Traits

**Amorphous.** The living spell can move through a space as narrow as 1 inch wide without squeezing.

**Magic Resistance.** The living spell has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The living spell makes two Magical Strike attacks.

**Magical Strike.** Melee Spell Attack: +7 to hit, reach 10 ft., one target. *Hit:* 21 (5d6 + 4) lightning damage.

**Spell Mimicry (Recharge 5–6).** The living spell unleashes a stroke of lightning in a line 100 feet long and 5 feet wide. Each creature in the line must make a DC 15 Dexterity saving throw, taking 28 (8d6) lightning damage on a failed save, or half as much damage on a successful one.


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