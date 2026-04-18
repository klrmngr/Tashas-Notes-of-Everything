---
type: pc
race: "Beast"
class:
 - "Space Eel"
subClass:
 - "CR 1/2"
cover: "Space Eel.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/small
  - cr/1-2
  - source/bam
---
###### Space Eel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Boo's Astral Menagerie
___

> [!infobox|no-t right]
> ![[Space Eel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Beast |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 7 (2d6) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Boo's Astral Menagerie |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 18 | 11 | 1 | 10 | 1 |
| **Mod** | +1 | +4 | +0 | -5 | +0 | -5 |

**Speed:** 10 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** —

---

### Traits

**Unusual Nature.** The eel doesn't require air.


---

### Actions

**Multiattack.** If it isn't attached to a creature, the eel makes one Bite attack and one Tail Spine attack.

**Bite.** Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. *Hit:* 4 (1d6 + 1) piercing damage, and the eel attaches to the target. While attached, the eel can't make Bite attacks. Instead, the target takes 4 (1d6 + 1) piercing damage at the start of each of the eel's turns. The eel can detach itself as a bonus action. A creature, including the target, can use its action to detach the eel.

**Tail Spine.** Melee Weapon Attack: +3 to hit, reach 5 ft., one creature. *Hit:* 3 (1d4 + 1) piercing damage, and the target must succeed on a DC 10 Constitution saving throw or be poisoned for 1 minute. Until this poison ends, the target is paralyzed. The target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.


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