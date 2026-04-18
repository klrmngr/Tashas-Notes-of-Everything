---
type: pc
race: "Monstrosity"
class:
 - "Corrupted Rat"
subClass:
 - "CR 0"
cover: "Corrupted Rat.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/tiny
  - cr/0
  - source/wtthc
---
###### Corrupted Rat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Corrupted Rat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Monstrosity |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 10 |
> | :FasHeart: HP | 1 (1d4 - 1) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 2 | 11 | 9 | 2 | 11 | 4 |
| **Mod** | -4 | +0 | -1 | -4 | +0 | -3 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 30 ft., passive Perception 11
**Languages:** —
**Skills:** Perception +2, Stealth +2

---

### Traits

**Agile.** The rat doesn't provoke Opportunity Attacks when it moves out of an enemy's reach.

**Death Burst.** The rat explodes when it dies. con DC 9, each creature in a 5-foot Emanation originating from the rat.  1 Acid damage.


---

### Actions

**Bite.** m +2, reach 5 ft. *Hit:* 1 Piercing damage.


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