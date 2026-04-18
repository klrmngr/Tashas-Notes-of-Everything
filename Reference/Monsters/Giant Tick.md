---
type: pc
race: "Monstrosity"
class:
 - "Giant Tick"
subClass:
 - "CR 2"
cover: "Giant Tick.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/medium
  - cr/2
  - source/bgg
---
###### Giant Tick
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Giant Tick.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Monstrosity |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 52 (7d8 + 21) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 10 | 16 | 2 | 10 | 2 |
| **Mod** | +3 | +0 | +3 | -4 | +0 | -4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 10
**Languages:** —

---

### Actions

**Proboscis.** Melee Weapon Attack: +5 to hit, reach 5 ft., one creature. *Hit:* 10 (2d6 + 3) piercing damage, and the tick attaches to the target. While attached, the tick can't make Proboscis attacks. The tick can detach itself by spending 5 feet of its movement. As an action, a creature within reach of the tick can try to detach the tick, doing so with a successful DC 13 Strength check.

**Blood Drain.** The tick deals 10 (2d6 + 3) necrotic damage to one creature it is physically attached to, provided that creature isn't a Construct or an Undead, or 17 (4d6 + 3) necrotic damage if the creature is a Giant. The tick regains hit points equal to the damage dealt.


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