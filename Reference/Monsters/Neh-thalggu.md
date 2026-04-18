---
type: pc
race: "Aberration"
class:
 - "Neh-thalggu"
subClass:
 - "CR 4"
cover: "Neh-thalggu.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/large
  - cr/4
  - source/bam
---
###### Neh-thalggu
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Neh-thalggu.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Aberration |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 95 (10d10 + 40) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 8 | 18 | 12 | 11 | 7 |
| **Mod** | +2 | -1 | +4 | +1 | +0 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Deep Speech; see also Brain Dump

---

### Traits

**Brain Dump.** Whenever the neh-thalggu consumes a brain, it gains the magical ability to speak and understand languages known by the brain's previous owner.

**Unusual Nature.** The neh-thalggu doesn't require air.


---

### Actions

**Multiattack.** The neh-thalggu makes one Bite attack and two Claw attacks.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 11 (2d8 + 2) piercing damage.

**Claw.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) slashing damage.

**Extract Brain.** Melee Weapon Attack: +4 to hit, reach 5 ft., one incapacitated Humanoid. *Hit:* 35 (10d6) piercing damage. If this damage reduces the target to 0 hit points, the neh-thalggu kills the target by extracting and consuming its brain.

**Mind Blast (Recharge 5–6).** The neh-thalggu magically emits psychic energy at one Humanoid it can see within 10 feet of itself. The target must make a DC 14 Wisdom saving throw. On a failed save, the target takes 9 (2d8) psychic damage and is incapacitated until the end of its next turn. On a successful save, the target takes half as much damage and isn't incapacitated.


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