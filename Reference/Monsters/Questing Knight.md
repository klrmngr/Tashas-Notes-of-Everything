---
type: pc
race: "Humanoid"
class:
 - "Questing Knight"
subClass:
 - "CR 12"
cover: "Questing Knight.png"
campaign:
locations:
tags:
  - race/humanoid
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/12
  - source/xmm
---
###### Questing Knight
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Questing Knight.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Small Humanoid |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC | 18 |
> | :FasHeart: HP | 202 (27d8 + 81) |
> | :FasUserGroup: Race | Humanoid |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 16 | 16 | 11 | 12 | 18 |
| **Mod** | +5 | +3 | +3 | +0 | +1 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 15
**Languages:** Common plus one other language
**Saving Throws:** Str +9, Con +7, Wis +5, Cha +8
**Skills:** Athletics +9, Perception +5, Persuasion +8
**Condition Immunities:** charmed; frightened

---

### Traits

**Aura of Bravery.** Creatures of the knight's choice in a 30-foot Emanation originating from it have Immunity to the Charmed and Frightened conditions while there.


---

### Actions

**Multiattack.** The knight makes three attacks, using Greatsword or Longbow in any combination.

**Greatsword.** m +9, reach 5 ft. *Hit:* 12 (2d6 + 5) Slashing damage plus 22 (5d8) Radiant damage.

**Longbow.** r +7, range 150/600 ft. *Hit:* 12 (2d8 + 3) Piercing damage plus 22 (5d8) Radiant damage.


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