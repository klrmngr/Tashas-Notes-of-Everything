---
type: pc
race: "Construct"
class:
 - "Skitterwidget"
subClass:
 - "CR 5"
cover: "Skitterwidget.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/medium
  - cr/5
  - source/cm
---
###### Skitterwidget
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Candlekeep Mysteries
___

> [!infobox|no-t right]
> ![[Skitterwidget.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Construct |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 18 (natural armor) |
> | :FasHeart: HP | 85 (10d8 + 40) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Candlekeep Mysteries |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 18 | 3 | 10 | 1 |
| **Mod** | +3 | +2 | +4 | -4 | +0 | -5 |

**Speed:** 30 ft., climb 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Skitterwidget
**Damage Immunities:** lightning; poison
**Condition Immunities:** blinded; deafened; exhaustion; paralyzed; petrified; poisoned

---

### Traits

**Lightning Absorption.** Whenever the skitterwidget is subjected to lightning damage, it takes no damage and instead regains a number of hit points equal to the lightning damage dealt.

**Unusual Nature.** The skitterwidget doesn't require air, food, drink, or sleep.


---

### Actions

**Multiattack.** The skitterwidget makes two attacks: one with its bite and one with its tail.

**Bite.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 10 (2d6 + 3) piercing damage. If the target is a creature, it is grappled by the skitterwidget (escape DC 13).

**Tail.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 10 (3d6) lightning damage, and if the target is a creature, it must succeed on a DC 15 Constitution saving throw or be stunned until the end of its next turn.


---

### Reactions

**Good Parent.** The skitterwidget imposes disadvantage on one attack roll made against a kiddywidget it can see within 5 feet of it.


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