---
type: pc
race: "Aberration"
class:
 - "Halog"
subClass:
 - "CR 7"
cover: "Halog.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/small
  - cr/7
  - source/coa
---
###### Halog
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: CoA
___

> [!infobox|no-t right]
> ![[Halog.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Aberration |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC | 14 (natural armor) |
> | :FasHeart: HP | 150 (20d6 + 80) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | CoA |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 13 | 14 | 18 | 4 | 8 | 8 |
| **Mod** | +1 | +2 | +4 | -3 | -1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 12
**Languages:** —
**Saving Throws:** Dex +5, Con +7
**Skills:** Athletics +4, Perception +2, Survival +5
**Condition Immunities:** poisoned

---

### Traits

**Adaptive Fangs.** The halog magically alters its fangs to inflict more damage on the creatures it hits (included in the attack).

**Magic Resistance.** The halog has advantage on saving throws against spells and other magical effects.

**Pack Tactics.** The halog gains advantage on attacks targeting creatures adjacent to one or more of the halog's conscious allies.


---

### Actions

**Multiattack.** The halog makes two Bite attacks.

**Bite.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 12 (3d6 + 2) piercing damage plus 10 (3d6) damage of a type that the target is most vulnerable to.


---

### Reactions

**Adaptive Hide.** After taking damage, the halog is now invulnerable to the damage type of the damage it just took, and any future damage of that type instead heals the halog by the damage amount. These benefits last until the halog uses this reaction again.


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