---
type: pc
race: "Humanoid"
class:
 - "Dragon Speaker"
subClass:
 - "CR 2"
cover: "Dragon Speaker.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/2
  - source/ftd
---
###### Dragon Speaker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Fizban's Treasury of Dragons
___

> [!infobox|no-t right]
> ![[Dragon Speaker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 13 (leather armor) |
> | :FasHeart: HP | 36 (8d6 + 8) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | Fizban's Treasury of Dragons |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 13 | 11 | 17 |
| **Mod** | +0 | +2 | +1 | +1 | +0 | +3 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Draconic, and any two languages
**Saving Throws:** Dex +4, Cha +5
**Skills:** Persuasion +5, Religion +3
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The speaker makes two Thunder Bolt attacks.

**Thunder Bolt.** Melee or Ranged Spell Attack: +5 to hit, reach 5 ft. or range 60 ft., one target. *Hit:* 13 (3d8) thunder damage, and the target is pushed horizontally up to 10 feet away from the speaker.


---

### Reactions

**Disarming Words (3/Day).** When a creature the speaker can see within 60 feet of it makes a damage roll, the speaker can roll a d6 and subtract the number rolled from that damage roll.


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