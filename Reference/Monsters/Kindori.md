---
type: pc
race: "Celestial"
class:
 - "Kindori"
subClass:
 - "CR 7"
cover: "Kindori.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/gargantuan
  - cr/7
  - source/bam
---
###### Kindori
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Kindori.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Gargantuan Celestial |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 202 (15d20 + 45) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 25 | 7 | 17 | 6 | 14 | 7 |
| **Mod** | +7 | -2 | +3 | -2 | +2 | -2 |

**Speed:** 0 ft., fly 60 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** —

---

### Traits

**Unusual Nature.** The kindori doesn't require food, drink, or air.


---

### Actions

**Tail.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 23 (3d10 + 7) bludgeoning damage.


---

### Bonus Actions

**Flashing Eyes (Recharge 6).** The kindori emits bright light in a 120-foot cone. Each creature in the cone must succeed on a DC 14 Wisdom saving throw or be blinded for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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