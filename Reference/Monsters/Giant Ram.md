---
type: pc
race: "Fey"
class:
 - "Giant Ram"
subClass:
 - "CR 1"
cover: "Giant Ram.png"
campaign:
locations:
tags:
  - race/fey
  - affinity/hostile
  - type/fey
  - size/large
  - cr/1
  - source/bgg
---
###### Giant Ram
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: BGG
___

> [!infobox|no-t right]
> ![[Giant Ram.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Large Fey |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 13 (natural armor) |
> | :FasHeart: HP | 28 (3d10 + 12) |
> | :FasUserGroup: Race | Fey |
> | :FasBook: Source | BGG |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 12 | 18 | 3 | 14 | 10 |
| **Mod** | +4 | +1 | +4 | -4 | +2 | +0 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** passive Perception 12
**Languages:** —
**Damage Resistances:** cold; fire; lightning

---

### Traits

**Magic Resistance.** The ram has advantage on saving throws against spells and other magical effects.


---

### Actions

**Ram.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d4 + 4) bludgeoning damage plus 3 (1d6) force damage. If the ram moved at least 20 feet straight toward the target immediately before the hit, the target must succeed on a DC 14 Strength saving throw or have the prone condition.

**Force Bolt.** Ranged Spell Attack: +4 to hit, range 30 ft., one target. *Hit:* 7 (2d6) force damage.


---

### Reactions

**Absorbent Fleece (Recharge 6).** Immediately after the ram succeeds on a saving throw against a spell or a spell's attack misses it, the ram can make one Force Bolt attack.


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