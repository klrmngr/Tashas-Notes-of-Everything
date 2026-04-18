---
type: pc
race: "Construct"
class:
 - "Servo"
subClass:
 - "CR 0"
cover: "Servo.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/0
  - source/psk
---
###### Servo
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: PSK
___

> [!infobox|no-t right]
> ![[Servo.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 0 (10 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 11 (natural armor) |
> | :FasHeart: HP | 10 (3d4 + 3) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | PSK |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 4 | 11 | 12 | 3 | 10 | 7 |
| **Mod** | -3 | +0 | +1 | -4 | +0 | -2 |

**Speed:** 20 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Damage Immunities:** poison
**Condition Immunities:** charmed; poisoned

---

### Actions

**Claw.** Melee Weapon Attack: +0 to hit, reach 5 ft., one target. *Hit:* 1 slashing damage.


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