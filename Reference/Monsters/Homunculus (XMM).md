---
type: pc
race: "Construct"
class:
 - "Homunculus"
subClass:
 - "CR 0"
cover: "Homunculus.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/0
  - source/xmm
---
###### Homunculus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Homunculus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 4 (1d4 + 2) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 15 | 14 | 10 | 10 | 7 |
| **Mod** | -3 | +2 | +2 | +0 | +0 | -2 |

**Speed:** 20 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** understands Common plus one other language but can't speak
**Saving Throws:** Wis +2, Cha +0
**Damage Immunities:** poison
**Condition Immunities:** charmed; poisoned

---

### Traits

**Telepathic Bond.** While the homunculus is on the same plane of existence as its master, the two of them can communicate telepathically with each other.


---

### Actions

**Bite.** m +4, reach 5 ft. *Hit:* 1 Piercing damage, and the target is subjected to the following effect. con DC 12.  The target has the Poisoned condition until the end of the homunculus's next turn. 5 The target has the Poisoned condition for 1 minute. While Poisoned, the target has the Unconscious condition, which ends early if the target takes any damage.


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