---
type: pc
race: "Monstrosity"
class:
 - "Horizonback Tortoise"
subClass:
 - "CR 8"
cover: "Horizonback Tortoise.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/8
  - source/egw
---
###### Horizonback Tortoise
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Horizonback Tortoise.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor); 22 while in its shell |
> | :FasHeart: HP | 227 (13d20 + 91) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 3 | 25 | 4 | 10 | 5 |
| **Mod** | +9 | -4 | +7 | -3 | +0 | -3 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft, passive Perception 10
**Languages:** understands Goblin but can't speak
**Saving Throws:** Str +12, Con +10
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Amphibious.** The tortoise can breathe air and water.

**Massive Frame.** The tortoise can carry up to 20,000 pounds of weight atop its shell, but moves at half speed if the weight exceeds 10,000 pounds. Medium or smaller creatures can move underneath the tortoise while it's not prone.
Any creature under the tortoise when it falls prone is grappled (escape DC 18). Until the grapple ends, the creature is prone and restrained.


---

### Actions

**Bite.** Melee Weapon Attack: +12 to hit, reach 10 ft., one target. *Hit:* 28 (3d12 + 9) bludgeoning damage.

**Shell Defense (Recharge 4–6).** The tortoise withdraws into its shell, falls prone, and gains a +5 bonus to AC. While the tortoise is in its shell, its speed is 0 and can't increase. The tortoise can emerge from its shell as an action, whereupon it is no longer prone.


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