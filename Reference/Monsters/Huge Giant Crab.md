---
type: pc
race: "Beast"
class:
 - "Huge Giant Crab"
subClass:
 - "CR 8"
cover: "Huge Giant Crab.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/8
  - source/tftyp
---
###### Huge Giant Crab
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tales from the Yawning Portal
___

> [!infobox|no-t right]
> ![[Huge Giant Crab.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 8 (3,900 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 161 (14d12 + 70) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Tales from the Yawning Portal |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 15 | 20 | 1 | 9 | 3 |
| **Mod** | +5 | +2 | +5 | -5 | -1 | -4 |

**Speed:** 30 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 9
**Languages:** —
**Skills:** Stealth +5
**Condition Immunities:** charmed; frightened; paralyzed

---

### Traits

**Banded Claw.** On one of its claws, the crab wears a rune-covered copper band that makes it immune to being charmed, frightened, and paralyzed. The copper band is worthless as a treasure, as the magic is keyed to this crab.

**Amphibious.** The crab can breathe air and water.


---

### Actions

**Claw.** Melee Weapon Attack: +9 to hit, reach 10 ft., one target. *Hit:* 27 (4d10 + 5) bludgeoning damage, and the target is grappled, escape DC 14. The crab has two claws, each of which can grapple only one target.


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