---
type: pc
race: "Monstrosity"
class:
 - "Crag Cat"
subClass:
 - "CR 1"
cover: "Crag Cat.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/1
  - source/skt
---
###### Crag Cat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Crag Cat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 34 (4d10 + 12) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 16 | 4 | 14 | 8 |
| **Mod** | +3 | +3 | +3 | -3 | +2 | -1 |

**Speed:** 40 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 14
**Languages:** —
**Skills:** Stealth +7, Perception +4

---

### Traits

**Nondetection.** The cat cannot be targeted or detected by any divination magic or perceived through magical scrying sensors.

**Pounce.** If the cat moves at least 20 feet straight toward a creature then hits it with a claw attack on the same turn, that target must succeed on a DC13 Strength saving throw or be knocked prone. If the target is prone, the cat can make one bite attack against it as a bonus action.

**Spell Turning.** The cat has advantage on saving throws against any spell that targets only the cat (not an area). If the cat's saving throw succeeds and the spell is of 7th level or lower, the spell has no effect on the cat and instead targets the caster.


---

### Actions

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 8 (1d10 + 3) piercing damage.

**Claw.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage.


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