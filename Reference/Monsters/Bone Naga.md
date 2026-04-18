---
type: pc
race: "Undead"
class:
 - "Bone Naga"
subClass:
 - "CR 4"
cover: "Bone Naga.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/large
  - cr/4
  - source/xmm
---
###### Bone Naga
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Bone Naga.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Large Undead |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 65 (10d10 + 10) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 15 | 16 | 12 | 16 | 15 | 15 |
| **Mod** | +2 | +3 | +1 | +3 | +2 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Common plus one other language
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; paralyzed; poisoned

---

### Actions

**Multiattack.** The naga makes two Bite attacks. It can replace any attack with a use of Serpentine Gaze.

**Bite.** m +5, reach 10 ft. *Hit:* 10 (2d6 + 3) Piercing damage plus 7 (2d6) Necrotic damage.

**Serpentine Gaze.** wis DC 13, one creature the naga can see within 60 feet.  13 (3d6 + 3) Psychic damage, and the target has the Charmed condition until the start of the naga's next turn.


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