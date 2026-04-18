---
type: pc
race: "Monstrosity"
class:
 - "Giant Corrupted Rat"
subClass:
 - "CR 1/2"
cover: "Giant Corrupted Rat.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/small
  - cr/1-2
  - source/wtthc
---
###### Giant Corrupted Rat
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: WttHC
___

> [!infobox|no-t right]
> ![[Giant Corrupted Rat.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Monstrosity |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 18 (4d6) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | WttHC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 7 | 16 | 12 | 2 | 10 | 4 |
| **Mod** | -2 | +3 | +1 | -4 | +0 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** —
**Skills:** Perception +12, Stealth +5

---

### Traits

**Death Burst.** The rat explodes when it dies. Constitution Saving Throw DC 11, each creature in a 5-foot Emanation originating from the rat.  5 (2d4) Acid damage.  Half damage.


---

### Actions

**Bite.** m +5, Reach 5 ft. *Hit:* 6 (1d6 + 3) Piercing damage plus 5 (2d4) Acid damage.


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