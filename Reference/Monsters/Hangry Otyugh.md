---
type: pc
race: "Aberration"
class:
 - "Hangry Otyugh"
subClass:
 - "CR 5"
cover: "Hangry Otyugh.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/5
  - source/awm
---
###### Hangry Otyugh
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Hangry Otyugh.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 114 |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 19 | 6 | 13 | 6 |
| **Mod** | +3 | +0 | +4 | -2 | +1 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Limited Telepathy.** The otyugh can magically transmit simple messages and images to any creature within 120 feet of it that can understand a language. This form of telepathy doesn't allow the receiving creature to telepathically respond.


---

### Actions

**Multiattack.** The otyugh makes three attacks:

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 12 (2d8 + 3) piercing damage. Target must make a DC 15 Constitution save, or take 6 (1d10) poison damage until cured.

**Tentacle.** Melee Weapon Attack: +6 to hit, reach 10 ft., one target. *Hit:* 7 (1d8 + 3) bludgeoning damage. Target must make a DC 19 Constitution save, or take 42 (12d6) poison damage.

**Slam!.** Target must make a DC 14 Constitution save, or be grappled.


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