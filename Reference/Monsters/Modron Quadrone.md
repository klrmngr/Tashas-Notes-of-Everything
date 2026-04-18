---
type: pc
race: "Construct"
class:
 - "Modron Quadrone"
subClass:
 - "CR 1"
cover: "Modron Quadrone.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1
  - source/xmm
---
###### Modron Quadrone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Modron Quadrone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 16 |
> | :FasHeart: HP | 22 (4d8 + 4) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 14 | 12 | 10 | 10 | 11 |
| **Mod** | +1 | +2 | +1 | +0 | +0 | +0 |

**Speed:** 30 ft., fly 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 12
**Languages:** Modron
**Skills:** Perception +2
**Condition Immunities:** charmed

---

### Traits

**Disintegration.** If the modron dies, it disintegrates into dust, leaving behind anything it was wearing or carrying.


---

### Actions

**Multiattack.** The modron makes four Slam attacks or four Gears Launcher attacks.

**Slam.** m +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Force damage.

**Gears Launcher.** r +4, range 320 ft. *Hit:* 4 (1d4 + 2) Force damage.


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