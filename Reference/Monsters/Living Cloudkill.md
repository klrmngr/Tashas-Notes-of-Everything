---
type: pc
race: "Construct"
class:
 - "Living Cloudkill"
subClass:
 - "CR 7"
cover: "Living Cloudkill.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/large
  - cr/7
  - source/erlw
---
###### Living Cloudkill
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Eberron: Rising from the Last War
___

> [!infobox|no-t right]
> ![[Living Cloudkill.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Large Construct |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 73 (7d10 + 35) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Eberron: Rising from the Last War |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 15 | 20 | 3 | 11 | 6 |
| **Mod** | +0 | +2 | +5 | -4 | +0 | -2 |

**Speed:** 25 ft., fly 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; exhaustion; frightened; grappled; poisoned; prone

---

### Traits

**Amorphous.** The living spell can move through a space as narrow as 1 inch wide without squeezing.

**Magic Resistance.** The living spell has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The living spell makes two Magical Strike attacks.

**Magical Strike.** Melee Spell Attack: +8 to hit, reach 10 ft., one target. *Hit:* 22 (5d6 + 5) poison damage.

**Spell Mimicry (Recharge 5–6).** The living spell creates a 40-foot-diameter sphere of fog within 60 feet of it (the fog spreads around corners). When a creature enters the fog for the first time on a turn or starts its turn there, it must make a DC 16 Constitution saving throw, taking 22 (5d8) poison damage on a failed save, or half as much damage on a successful one.
The fog moves 10 feet away from the living spell at the start of each of its turns, rolling along the ground and through openings. The fog lasts for 10 minutes or until the living spell's concentration ends (as if concentrating on a spell).


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