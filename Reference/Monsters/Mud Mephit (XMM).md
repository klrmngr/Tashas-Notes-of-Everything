---
type: pc
race: "Elemental"
class:
 - "Mud Mephit"
subClass:
 - "CR 1/4"
cover: "Mud Mephit.png"
campaign:
locations:
tags:
  - race/elemental
  - affinity/hostile
  - type/elemental
  - size/small
  - cr/1-4
  - source/xmm
---
###### Mud Mephit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Mud Mephit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Elemental |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 11 |
> | :FasHeart: HP | 13 (3d6 + 3) |
> | :FasUserGroup: Race | Elemental |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 8 | 12 | 12 | 9 | 11 | 7 |
| **Mod** | -1 | +1 | +1 | -1 | +0 | -2 |

**Speed:** 20 ft., fly 20 ft., swim 20 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Primordial (Aquan, Terran)
**Skills:** Stealth +3
**Damage Immunities:** poison
**Condition Immunities:** exhaustion; poisoned

---

### Traits

**Death Burst.** The mephit explodes when it dies. dex DC 11, each creature in a 5-foot Emanation originating from the mephit.  The target has the Restrained condition until the end of its next turn.


---

### Actions

**Slam.** m +3, reach 5 ft. *Hit:* 4 (1d6 + 1) Bludgeoning damage.

**Mud Breath (Recharge 6).** dex DC 11, one creature the mephit can see within 15 feet.  The target has the Restrained condition until the end of the mephit's next turn.


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