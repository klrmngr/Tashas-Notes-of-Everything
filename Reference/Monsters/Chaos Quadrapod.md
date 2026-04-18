---
type: pc
race: "Aberration"
class:
 - "Chaos Quadrapod"
subClass:
 - "CR 4"
cover: "Chaos Quadrapod.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/4
  - source/ai
---
###### Chaos Quadrapod
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Acquisitions Incorporated
___

> [!infobox|no-t right]
> ![[Chaos Quadrapod.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 52 (7d10 + 14) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Acquisitions Incorporated |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 13 | 15 | 6 | 10 | 4 |
| **Mod** | +4 | +1 | +2 | -2 | +0 | -3 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** blindsight 120 ft. (blind beyond this radius), passive Perception 14
**Languages:** —
**Skills:** Acrobatics +5, Perception +4

---

### Traits

**Magic Resistance.** The chaos quadrapod has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The chaos quadrapod makes up to two tentacle attacks.

**Tentacle.** Melee Weapon Attack: +6 to hit, reach 15 ft., one target. *Hit:* 11 (2d6 + 4) bludgeoning damage. If the target is a creature, it is grappled (escape DC 14). Until this grapple ends, the target is restrained. The chaos quadrapod can grapple no more than two targets at a time.

**Chaos Cloud (Recharges after a Short or Long Rest).** The chaos quadrapod shoots forth a knot of roiling ethereal light that explodes at a point it can see within 60 feet of it. Each creature in a 20-foot-radius sphere centered on that point must succeed on a DC 14 Charisma saving throw or be stunned until the end of its next turn.


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