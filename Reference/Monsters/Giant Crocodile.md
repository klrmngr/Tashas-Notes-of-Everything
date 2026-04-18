---
type: pc
race: "Beast"
class:
 - "Giant Crocodile"
subClass:
 - "CR 5"
cover: "Giant Crocodile.png"
campaign:
locations:
tags:
  - race/beast
  - affinity/hostile
  - type/beast
  - size/huge
  - cr/5
  - source/mm
---
###### Giant Crocodile
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Giant Crocodile.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Huge Beast |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 85 (9d12 + 27) |
> | :FasUserGroup: Race | Beast |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 9 | 17 | 2 | 10 | 7 |
| **Mod** | +5 | -1 | +3 | -4 | +0 | -2 |

**Speed:** 30 ft., swim 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —
**Skills:** Stealth +5

---

### Traits

**Hold Breath.** The crocodile can hold its breath for 30 minutes.


---

### Actions

**Multiattack.** The crocodile makes two attacks: one with its bite and one with its tail.

**Bite.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 21 (3d10 + 5) piercing damage, and the target is grappled (escape DC 16). Until this grapple ends, the target is restrained, and the crocodile can't bite another target.

**Tail.** Melee Weapon Attack: +8 to hit, reach 10 ft., one target not grappled by the crocodile. *Hit:* 14 (2d8 + 5) bludgeoning damage. If the target is a creature, it must succeed on a DC 16 Strength saving throw or be knocked prone.


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