---
type: pc
race: "Plant"
class:
 - "Gas Spore Fungus"
subClass:
 - "CR 1/2"
cover: "Gas Spore Fungus.png"
campaign:
locations:
tags:
  - race/plant
  - affinity/hostile
  - type/plant
  - size/large
  - cr/1-2
  - source/xmm
---
###### Gas Spore Fungus
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Gas Spore Fungus.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Large Plant |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 8 |
> | :FasHeart: HP | 13 (9d10 - 36) |
> | :FasUserGroup: Race | Plant |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 5 | 1 | 3 | 1 | 1 | 1 |
| **Mod** | -3 | -5 | -4 | -5 | -5 | -5 |

**Speed:** 5 ft., fly 10 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Blindsight 30 ft., passive Perception 5
**Languages:** —
**Damage Immunities:** poison
**Condition Immunities:** blinded; charmed; deafened; frightened; paralyzed; poisoned; prone

---

### Traits

**Death Burst.** The gas spore bursts when it dies. con DC 10, each creature in a 20-foot Emanation originating from the gas spore.  The target takes 10 (3d6) Poison damage and has the Poisoned condition for 1d12 hours. Unless the Poisoned condition is removed, the target dies at the end of that time and sprouts 2d4 Tiny Gas Spore Fungi (each with 1 Hit Point). After 2d6 days, they become Large and have 13 Hit Points.


---

### Actions

**Tendril.** m +0, reach 5 ft. *Hit:* 3 (1d6) Poison damage, and the target has the Poisoned condition until the end of its next turn.


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