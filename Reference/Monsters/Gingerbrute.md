---
type: pc
race: "Construct"
class:
 - "Gingerbrute"
subClass:
 - "CR 1/2"
cover: "Gingerbrute.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/tiny
  - cr/1-2
  - source/mcv4ec
---
###### Gingerbrute
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MCV4EC
___

> [!infobox|no-t right]
> ![[Gingerbrute.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Tiny Construct |
> | :FasRulerVertical: Size | Tiny |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 14 |
> | :FasHeart: HP | 18 (4d4 + 8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | MCV4EC |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 18 | 14 | 7 | 10 | 12 |
| **Mod** | +1 | +4 | +2 | -2 | +0 | +1 |

**Speed:** 60 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** one language of its creator
**Skills:** Acrobatics +6, Athletics +3
**Damage Vulnerabilities:** bludgeoning
**Condition Immunities:** exhaustion

---

### Traits

**Can't Catch Me.** The gingerbrute has advantage on any ability checks or saving throws it makes to avoid or end the grappled or the restrained condition on itself.

**Sweet Victory.** Once the gingerbrute is destroyed, a creature can use its action to eat all the remains and gain 5 temporary hit points. The remains crumble away after 24 hours if not eaten.


---

### Actions

**Multiattack.** The gingerbrute makes two Fork attacks, two Gumdrop Slingshot attacks, or one of each.

**Fork.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4 + 4) piercing damage.

**Gumdrop Slingshot.** Ranged Weapon Attack: +6 to hit, range 30/120 ft., one target. *Hit:* 6 (1d4 + 4) bludgeoning damage.


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