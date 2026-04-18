---
type: pc
race: "Construct"
class:
 - "Kiddywidget"
subClass:
 - "CR 1/2"
cover: "Kiddywidget.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-2
  - source/cm
---
###### Kiddywidget
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Kiddywidget.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/2 (100 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 15 (2d6 + 8) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 6 | 14 | 18 | 1 | 10 | 1 |
| **Mod** | -2 | +2 | +4 | -5 | +0 | -5 |

**Speed:** 20 ft., climb 20 ft. &nbsp;|&nbsp; **Senses:** darkvision 60, passive Perception 10
**Languages:** Skitterwidget
**Damage Immunities:** lightning; poison
**Condition Immunities:** blinded; deafened; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Unusual Nature.** The kiddywidget doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The kiddywidget makes two attacks: one with its bite and one with its tail.

**Bite.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage. If the target is a creature, it is grappled by the kiddywidget (escape DC 8).

**Tail.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 2 (1d4) lightning damage.


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