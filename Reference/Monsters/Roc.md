---
type: pc
race: "Monstrosity"
class:
 - "Roc"
subClass:
 - "CR 11"
cover: "Roc.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/gargantuan
  - cr/11
  - source/mm
---
###### Roc
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Monster Manual
___

> [!infobox|no-t right]
> ![[Roc.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 11 (7,200 XP) |
> | :RiSwordFill: Type | Gargantuan Monstrosity |
> | :FasRulerVertical: Size | Gargantuan |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 248 (16d20 + 80) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Monster Manual |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 28 | 10 | 20 | 3 | 10 | 9 |
| **Mod** | +9 | +0 | +5 | -4 | +0 | -1 |

**Speed:** 20 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** passive Perception 14
**Languages:** —
**Saving Throws:** Dex +4, Con +9, Wis +4, Cha +3
**Skills:** Perception +4

---

### Traits

**Keen Sight.** The roc has advantage on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The roc makes two attacks: one with its beak and one with its talons.

**Beak.** Melee Weapon Attack: +13 to hit, reach 10 ft., one target. *Hit:* 27 (4d8 + 9) piercing damage.

**Talons.** Melee Weapon Attack: +13 to hit, reach 5 ft., one target. *Hit:* 23 (4d6 + 9) slashing damage, and the target is grappled (escape DC 19). Until this grapple ends, the target is restrained, and the roc can't use its talons on another target.


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