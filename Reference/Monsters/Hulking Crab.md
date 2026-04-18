---
type: pc
race: "Beast"
class:
 - "Hulking Crab"
subClass:
 - "CR 5"
cover: "Hulking Crab.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/5
  - source/skt
---
###### Hulking Crab
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Storm King's Thunder
___

> [!infobox|no-t right]
> ![[Hulking Crab.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 76 (8d12 + 24) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Storm King's Thunder |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 8 | 16 | 3 | 11 | 3 |
| **Mod** | +4 | -1 | +3 | -4 | +0 | -4 |

**Speed:** 20 ft., swim 30 ft. &nbsp;|&nbsp; **Senses:** blindsight 30 ft., passive Perception 10
**Languages:** —
**Skills:** Stealth +2

---

### Traits

**Amphibious.** The crab can breathe air and water.

**Shell Camouflage.** While the crab remains motionless with its eyestalks and pincers tucked close to its body, it resembles a natural formation or a pile of detritus. A creature within 30 feet of it can discern its true nature with a successful DC 15 Intelligence (Nature) check.


---

### Actions

**Multiattack.** The crab makes two attacks with its claws.

**Claw.** Melee Weapon Attack: +7 to hit, reach 10 ft., one target. *Hit:* 20 (3d10 + 4) bludgeoning damage, and the target is grappled (escape DC 15). The crab has two claws, each of which can grapple only one target


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