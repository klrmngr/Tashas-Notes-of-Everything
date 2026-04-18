---
type: pc
race: "Construct"
class:
 - "Pidlwick II"
subClass:
 - "CR 1/4"
cover: "Pidlwick II.png"
campaign:
locations:
tags:
  - race/construct
  - affinity/hostile
  - type/construct
  - size/small
  - cr/1-4
  - source/cos
---
###### Pidlwick II
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Curse of Strahd
___

> [!infobox|no-t right]
> ![[Pidlwick II.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1/4 (50 XP) |
> | :RiSwordFill: Type | Small Construct |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 10 (3d6) |
> | :FasUserGroup: Race | Construct |
> | :FasBook: Source | Curse of Strahd |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 10 | 14 | 11 | 8 | 13 | 10 |
| **Mod** | +0 | +2 | +0 | -1 | +1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** understands Common but doesn't speak and can't read or write
**Skills:** Performance +2
**Damage Immunities:** poison
**Condition Immunities:** paralyzed; petrified; poisoned

---

### Traits

**Ambusher.** During the first round of combat, Pidlwick II has advantage on attack rolls against any creature that hasn't had a turn yet.


---

### Actions

**Club.** Melee Weapon Attack: +2 to hit, reach 5 ft., one target. *Hit:* 2 (1d4) bludgeoning damage.

**Dart.** Ranged Weapon Attack: +4 to hit, range 20/60 ft., one target. *Hit:* 4 (1d4 + 2) piercing damage.


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