---
type: pc
race: "Undead"
class:
 - "Ghast Gravecaller"
subClass:
 - "CR 6"
cover: "Ghast Gravecaller.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/6
  - source/xmm
---
###### Ghast Gravecaller
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Ghast Gravecaller.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 97 (15d8 + 30) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 17 | 14 | 18 | 14 | 8 |
| **Mod** | +3 | +3 | +2 | +4 | +2 | -1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 12
**Languages:** Abyssal, Common
**Saving Throws:** Con +5, Wis +5
**Damage Immunities:** necrotic; poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Traits

**Stench.** con DC 13, any creature that starts its turn in a 5-foot Emanation originating from the ghast.  The target has the Poisoned condition until the start of its next turn.  The target is immune to this ghast's Stench for 24 hours.


---

### Actions

**Multiattack.** The ghast makes two Horrific Necrosis attacks. It can replace one attack with a Claw attack.

**Claw.** m +6, reach 5 ft. *Hit:* 13 (3d6 + 3) Slashing damage. If the target isn't an Undead, it has the Paralyzed condition until the end of its next turn.

**Horrific Necrosis.** m,r +7, reach 5 ft. or range 120 ft. *Hit:* 15 (2d10 + 4) Necrotic damage, and the target has the Frightened condition until the end of its next turn.


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