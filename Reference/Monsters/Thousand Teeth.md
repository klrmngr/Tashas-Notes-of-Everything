---
type: pc
race: "Monstrosity"
class:
 - "Thousand Teeth"
subClass:
 - "CR 6"
cover: "Thousand Teeth.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/6
  - source/gos
---
###### Thousand Teeth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Thousand Teeth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 10 | 17 | 2 | 10 | 7 |
| **Mod** | +4 | +0 | +3 | -4 | +0 | -2 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Saving Throws:** Str +7, Con +6
**Skills:** Athletics +7, Stealth +3

---

### Traits

**Hold Breath.** Thousand Teeth can hold its breath for 30 minutes.

**Legendary Resistance (2/Day).** If Thousand Teeth fails a saving throw, it can choose to succeed instead.


---

### Actions

**Multiattack.** Thousand Teeth makes two attacks: one with its bite and one with its tail.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 15 (2d10 + 4) piercing damage.

**Tail.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 8 (1d8 + 4) bludgeoning damage. If the target is a creature, it must succeed on a DC 15 Strength saving throw or be knocked prone.


---

### Legendary Actions

### 

**Detect.** Thousand Teeth makes a Wisdom (Perception) check.

**Lunge.** Thousand Teeth moves up to half its speed.

**Bite (Costs 2 Actions).** Thousand Teeth makes a bite attack.


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