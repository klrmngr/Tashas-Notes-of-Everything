---
type: pc
race: "Undead"
class:
 - "Lacedon Ghoul"
subClass:
 - "CR 1"
cover: "Lacedon Ghoul.png"
campaign:
locations:
tags:
  - race/undead
  - affinity/hostile
  - type/undead
  - size/medium
  - cr/1
  - source/xmm
---
###### Lacedon Ghoul
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Lacedon Ghoul.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Undead |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 12 |
> | :FasHeart: HP | 22 (5d8) |
> | :FasUserGroup: Race | Undead |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 15 | 10 | 7 | 10 | 6 |
| **Mod** | +1 | +2 | +0 | -2 | +0 | -2 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 10
**Languages:** Common
**Damage Resistances:** cold
**Damage Immunities:** poison
**Condition Immunities:** charmed; exhaustion; poisoned

---

### Actions

**Multiattack.** The ghoul makes two Icy Bite attacks.

**Icy Bite.** m +4, reach 5 ft. *Hit:* 9 (2d6 + 2) Cold damage, and the target's Speed decreases by 5 feet until the start of the ghoul's next turn.

**Claw.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Slashing damage. If the target is a creature that isn't an Undead or elf, it is subjected to the following effect. con DC 10.  The target has the Paralyzed condition until the end of its next turn.


---

### Bonus Actions

**Watery Rush.** While underwater, the ghoul moves up to half its Swim Speed without provoking Opportunity Attacks.


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