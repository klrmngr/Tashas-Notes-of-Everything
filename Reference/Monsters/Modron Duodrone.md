---
type: pc
race: "Construct"
class:
 - "Modron Duodrone"
subClass:
 - "CR 1/4"
cover: "Modron Duodrone.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/1-4
  - source/xmm
---
###### Modron Duodrone
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Modron Duodrone.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 15 |
> | :FasHeart: HP | 11 (2d8 + 2) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 13 | 12 | 6 | 10 | 7 |
| **Mod** | +0 | +1 | +1 | -2 | +0 | -2 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** Truesight 120 ft., passive Perception 10
**Languages:** Modron
**Condition Immunities:** charmed

---

### Traits

**Disintegration.** If the modron dies, it disintegrates into dust, leaving behind anything it was wearing or carrying.


---

### Actions

**Multiattack.** The modron makes two Clockwork Blade attacks.

**Clockwork Blade.** m,r +3, reach 5 ft. or range 30 ft. *Hit:* 4 (1d6 + 1) Force damage. The blade magically returns to the modron's hand immediately after a ranged attack.


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