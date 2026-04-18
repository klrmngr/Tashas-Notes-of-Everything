---
type: pc
race: "Beast"
class:
 - "Kavu Predator"
subClass:
 - "CR 2"
cover: "Kavu Predator.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/large
  - cr/2
  - source/psd
---
###### Kavu Predator
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSD
___

> [!infobox|no-t right]
> ![[Kavu Predator.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Large Beast |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 75 (10d10 + 20) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | PSD |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 12 | 15 | 6 | 14 | 8 |
| **Mod** | +4 | +1 | +2 | -2 | +2 | -1 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** understands Elvish
**Skills:** Perception +4, Stealth +5

---

### Traits

**Pounce.** If the kavu moves at least 20 feet straight toward a creature and then hits it with a claw attack on the same turn, that target must succeed on a DC 14 Strength saving throw or be knocked prone. If the target is prone, the kavu can make one bite attack against it as a bonus action.


---

### Actions

**Multiattack.** The kavu makes two claw attacks.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) piercing damage.

**Claw.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) slashing damage.


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