---
type: pc
race: "Construct"
class:
 - "Modron Monodrone"
subClass:
 - "CR 1/8"
cover: "Modron Monodrone.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-8
  - source/xmm
---
###### Modron Monodrone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Modron Monodrone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/8 (25 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 5 (1d8 + 1) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 12 | 4 | 10 | 5 |
| **Mod** | +0 | +2 | +1 | -3 | +0 | -3 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 10
**Languages:** Modron
**Condition Immunities:** charmed

---

### Traits

**Disintegration.** If the modron dies, it disintegrates into dust, leaving behind anything it was wearing or carrying.


---

### Actions

**Gear.** m +4, reach 5 ft. *Hit:* 6 (1d8 + 2) Force damage.

**Gear Flinger.** r +4, range 120 ft. *Hit:* 6 (1d8 + 2) Force damage.


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