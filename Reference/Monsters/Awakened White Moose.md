---
type: pc
race: "Beast"
class:
 - "Awakened White Moose"
subClass:
 - "CR 3"
cover: "Awakened White Moose.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/3
  - source/idrotf
---
###### Awakened White Moose
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Awakened White Moose.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 68 (8d10 + 24) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 11 | 16 | 10 | 12 | 6 |
| **Mod** | +4 | +0 | +3 | +0 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** Druidic

---

### Traits

**Charge.** If the moose moves at least 20 feet straight toward a target and then hits it with an antlers attack on the same turn, the target takes an extra 9 (2d8) bludgeoning damage. If the target is a creature, it must succeed on a DC 14 Strength saving throw or be knocked prone.

**Sure-Footed.** The moose has advantage on Strength and Dexterity saving throws made against effects that would knock it prone.


---

### Actions

**Multiattack.** The moose makes two attacks: one with its antlers and one with its hooves.

**Antlers.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) piercing damage.

**Hooves.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage.


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