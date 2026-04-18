---
type: pc
race: "Monstrosity"
class:
 - "Maw of Sekolah"
subClass:
 - "CR 7"
cover: "Maw of Sekolah.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/huge
  - cr/7
  - source/gos
---
###### Maw of Sekolah
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Ghosts of Saltmarsh
___

> [!infobox|no-t right]
> ![[Maw of Sekolah.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Monstrosity |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 12 (natural armor) |
> | :FasHeart: HP | 114 (12d12 + 36) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Ghosts of Saltmarsh |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 12 | 17 | 2 | 14 | 7 |
| **Mod** | +5 | +1 | +3 | -4 | +2 | -2 |

**Speed:** 0 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 15
**Languages:** Sahuagin, telepathy 100 ft.
**Saving Throws:** Str +8, Con +6
**Skills:** Athletics +8, Perception +5

---

### Traits

**Legendary Resistance (2/Day).** If the maw of Sekolah fails a saving throw, it can choose to succeed instead.

**Water Breathing.** The maw of Sekolah can breathe only underwater.


---

### Actions

**Multiattack.** The maw of Sekolah makes one attack with its bite and one attack with its tail smash.

**Bite.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 16 (2d10 + 5) piercing damage.

**Tail Smash.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target. *Hit:* 9 (1d8 + 5) bludgeoning damage.


---

### Legendary Actions

### 

**Detect.** The maw of Sekolah makes a Wisdom (Perception) check.

**Speed of Sekolah.** The maw of Sekolah moves up to its speed.

**Feed (Costs 2 Actions).** The ferocious spirit of Sekolah flashes through the water, tearing through the foes of the maw of Sekolah. Each creature of the maw's choosing within 60 feet of it must make a DC 16 Dexterity saving throw, taking 7 (2d6) slashing damage on a failed save, or half as much damage on a successful one.


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