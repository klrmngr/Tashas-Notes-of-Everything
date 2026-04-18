---
type: pc
race: "Beast"
class:
 - "Gremlin"
subClass:
 - "CR 1/2"
cover: "Gremlin.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/1-2
  - source/psk
---
###### Gremlin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSK
___

> [!infobox|no-t right]
> ![[Gremlin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | PSK |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 13 | 13 | 3 | 13 | 6 |
| **Mod** | +1 | +1 | +1 | -4 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** —

---

### Traits

**Aether Scent.** The gremlin can pinpoint, by scent, the location of refined or unrefined aether within 30 feet of it.


---

### Actions

**Claws.** Melee Weapon Attack: +3 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage.

**Siphon.** The gremlin drains aether from an aether-powered device it can see within 5 feet of it. If the object isn't being worn or carried, the touch automatically drains aether. If the object is being worn or carried by a creature, the creature must succeed on a DC 11 Dexterity saving throw to keep it out of the gremlin's reach.
If the aether-powered device grants any bonus (to attack rolls, damage rolls, Armor Class, and so on), that bonus is reduced by 1. If the device has charges, it loses 1 charge. Otherwise, it stops functioning for 1 round. Left unhindered, a gremlin can completely destroy an aether-powered device.


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