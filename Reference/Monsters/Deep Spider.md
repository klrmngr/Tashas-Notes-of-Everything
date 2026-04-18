---
type: pc
race: "Beast"
class:
 - "Deep Spider"
subClass:
 - "CR 7"
cover: "Deep Spider.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/7
  - source/mabjov
---
###### Deep Spider
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MaBJoV
___

> [!infobox|no-t right]
> ![[Deep Spider.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 95 (10d12 + 30) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | MaBJoV |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 20 | 14 | 16 | 6 | 12 | 4 |
| **Mod** | +5 | +2 | +3 | -2 | +1 | -3 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** tremorsense 60 ft., passive Perception 11
**Languages:** —
**Skills:** Stealth +8

---

### Traits

**Spider Climb.** The deep spider can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Web Sense.** While in contact with a web, the deep spider knows the exact location of any other creature in contact with the same web.

**Web Walker.** The deep spider ignores movement restrictions caused by webbing.


---

### Actions

**Multiattack.** The deep spider makes one Bite attack and two Foreleg attacks.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage, and the target must make a DC 14 Constitution saving throw, taking 18 (4d8) poison damage on a failed save, or half as much damage on a successful one. If the poison damage reduces the target to 0 hit points, the target is stable but poisoned for 1 hour, even after regaining hit points, and has the paralyzed condition while poisoned in this way.

**Foreleg.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 19 (4d6 + 5) slashing damage.


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