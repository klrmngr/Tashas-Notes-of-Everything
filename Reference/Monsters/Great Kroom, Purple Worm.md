---
type: pc
race: "Monstrosity"
class:
 - "Great Kroom, Purple Worm"
subClass:
 - "CR 15"
cover: "Great Kroom, Purple Worm.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/15
  - source/awm
---
###### Great Kroom, Purple Worm
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: AWM
___

> [!infobox|no-t right]
> ![[Great Kroom, Purple Worm.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 247 |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | AWM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 13 | 12 | 11 | 11 | 12 |
| **Mod** | +0 | +1 | +1 | +0 | +0 | +1 |

**Speed:** 50 ft., burrow 30 ft. &nbsp;|&nbsp; **Senses:** —
**Languages:** —

---

### Traits

**Tunneler.** The worm can burrow through solid rock at half its burrow speed and leaves a 10-foot-diameter tunnel in its wake.


---

### Actions

**Multiattack.** The worm makes two attacks:

**Bite.** Melee Weapon Attack: +14 to hit, one target. *Hit:* 22 (3d8) piercing damage. Target must make a DC 19 Dexterity save, or be swallowed by the worm!

**Tail Stinger.** Melee Weapon Attack: +14 to hit, one creature. *Hit:* 19 (3d6 + 9) piercing damage Target must make a DC 19 Constitution save, or take 42 (12d6) poison damage.


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