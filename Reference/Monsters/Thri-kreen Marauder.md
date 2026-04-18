---
type: pc
race: "Monstrosity"
class:
 - "Thri-kreen Marauder"
subClass:
 - "CR 1"
cover: "Thri-kreen Marauder.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/1
  - source/xmm
---
###### Thri-kreen Marauder
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Thri-kreen Marauder.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 33 (6d8 + 6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 15 | 13 | 8 | 12 | 7 |
| **Mod** | +1 | +2 | +1 | -1 | +1 | -2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 13
**Languages:** Thri-kreen; telepathy 60 ft.
**Skills:** Perception +3, Stealth +4, Survival +3

---

### Actions

**Multiattack.** The thri-kreen makes two attacks, using Gythka or Chatkcha in any combination.

**Gythka.** m +3, reach 5 ft. *Hit:* 5 (1d8 + 1) Slashing damage plus 2 (1d4) Poison damage.

**Chatkcha.** r +4, range 30/120 ft. *Hit:* 5 (1d6 + 2) Slashing damage.


---

### Bonus Actions

**Leap.** The thri-kreen jumps up to 15 feet by spending 5 feet of movement.


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