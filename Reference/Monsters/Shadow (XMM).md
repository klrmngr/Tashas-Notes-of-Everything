---
type: pc
race: "Undead"
class:
 - "Shadow"
subClass:
 - "CR 1/2"
cover: "Shadow.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1-2
  - source/xmm
---
###### Shadow
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Shadow.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 27 (5d8 + 5) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 13 | 6 | 10 | 8 |
| **Mod** | -2 | +2 | +1 | -2 | +0 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** —
**Skills:** Stealth +6
**Damage Vulnerabilities:** radiant
**Damage Resistances:** acid; cold; fire; lightning; thunder
**Damage Immunities:** necrotic; poison
**Condition Immunities:** exhaustion; frightened; grappled; paralyzed; petrified; poisoned; prone; restrained; unconscious

---

### Traits

**Amorphous.** The shadow can move through a space as narrow as 1 inch without expending extra movement to do so.

**Sunlight Weakness.** While in sunlight, the shadow has Disadvantage on D20 Tests.


---

### Actions

**Draining Swipe.** m +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Necrotic damage, and the target's Strength score decreases by 1d4. The target dies if this reduces that score to 0. If a Humanoid is slain by this attack, a Shadow rises from the corpse 1d4 hours later.


---

### Bonus Actions

**Shadow Stealth.** While in Dim Light or Darkness, the shadow takes the Hide action.


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