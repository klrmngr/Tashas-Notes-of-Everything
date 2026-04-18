---
type: pc
race: "Humanoid (gnoll)"
class:
 - "Gnoll Pack Lord"
subClass:
 - "CR 2"
cover: "Gnoll Pack Lord.png"
campaign:
locations:
tags:
  - race/gnoll
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mm
---
###### Gnoll Pack Lord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Gnoll Pack Lord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (gnoll) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Humanoid (gnoll) |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 13 | 8 | 11 | 9 |
| **Mod** | +3 | +2 | +1 | -1 | +0 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Gnoll

---

### Traits

**Rampage.** When the gnoll reduces a creature to 0 hit points with a melee attack on its turn, the gnoll can take a bonus action to move up to half its speed and make a bite attack.


---

### Actions

**Multiattack.** The gnoll makes two attacks, either with its glaive or its longbow, and uses its Incite Rampage if it can.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 5 (1d4 + 3) piercing damage.

**Glaive.** Melee Weapon Attack: +5 to hit, reach 10 ft., one target. *Hit:* 8 (1d10 + 3) slashing damage.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 6 (1d8 + 2) piercing damage.

**Incite Rampage (Recharge 5–6).** One creature the gnoll can see within 30 feet of it can use its reaction to make a melee attack if it can hear the gnoll and has the Rampage trait.


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