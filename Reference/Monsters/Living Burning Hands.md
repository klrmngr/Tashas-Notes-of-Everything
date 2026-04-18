---
type: pc
race: "Construct"
class:
 - "Living Burning Hands"
subClass:
 - "CR 1"
cover: "Living Burning Hands.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/erlw
---
###### Living Burning Hands
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Living Burning Hands.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 15 (2d8 + 6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 12 | 16 | 3 | 6 | 6 |
| **Mod** | +0 | +1 | +3 | -4 | -2 | -2 |

**Speed:** 25 ft., fly 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 8
**Languages:** —
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** fire
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; poisoned; prone

---

### Traits

**Amorphous.** The living spell can move through a space as narrow as 1 inch wide without squeezing.

**Magic Resistance.** The living spell has advantage on saving throws against spells and other magical effects.


---

### Actions

**Magical Strike.** Melee Spell Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) fire damage.

**Spell Mimicry (Recharge 5–6).** The living spell unleashes a thin sheet of flames in a 15-foot cone. Each creature in that area must make a DC 13 Dexterity saving throw, taking 10 (3d6) fire damage on a failed save, or half as much damage on a successful one.


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