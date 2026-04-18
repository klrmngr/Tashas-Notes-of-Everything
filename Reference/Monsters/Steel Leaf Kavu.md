---
type: pc
race: "Beast"
class:
 - "Steel Leaf Kavu"
subClass:
 - "CR 4"
cover: "Steel Leaf Kavu.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/4
  - source/psd
---
###### Steel Leaf Kavu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSD
___

> [!infobox|no-t right]
> ![[Steel Leaf Kavu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 142 (15d10 + 60) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | PSD |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 12 | 18 | 6 | 14 | 8 |
| **Mod** | +5 | +1 | +4 | -2 | +2 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** understands Elvish
**Skills:** Perception +4

---

### Traits

**Raking Charge.** If the kavu moves at least 20 feet straight toward a creature and then hits it with a bite attack on the same turn, that target must succeed on a DC 15 Strength saving throw or be knocked prone. If the target is prone, the kavu can make one rend attack against it as a bonus action.


---

### Actions

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage.

**Rend.** Melee Weapon Attack: +7 to hit, reach 5 ft., one prone creature. *Hit:* 23 (4d8 + 5) slashing damage.


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