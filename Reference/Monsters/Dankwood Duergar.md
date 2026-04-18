---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Dankwood Duergar"
subClass:
 - "CR 2"
cover: "Dankwood Duergar.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mgelft
---
###### Dankwood Duergar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MGELFT
___

> [!infobox|no-t right]
> ![[Dankwood Duergar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | — |
> | :FasShield: AC | 18 (Plate Mail) |
> | :FasHeart: HP | 26 (4d8 + 8) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | MGELFT |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 11 | 14 | 11 | 10 | 9 |
| **Mod** | +3 | +0 | +2 | +0 | +0 | -1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Dwarvish, Undercommon
**Damage Resistances:** poison

---

### Traits

**Duergar Resilience.** The Dankwood duergar has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed.

**Sunlight Sensitivity.** While in sunlight, the Dankwood duergar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Verbal Jab.** The duergar unleashes a string of insults laced with subtle enchantments at a creature they can see within 60 feet. If the creature can hear them (it doesn't need to understand them), it must succeed on a DC 12 Wisdom saving throw or take 1d4 psychic damage and have disadvantage on the next attack roll it makes before the end of its next turn.

**Haymaker.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 9 (1d6 + 6) bludgeoning damage. If the duergar is enlarged, increase their damage to 10 (2d6 + 3) bludgeoning damage.


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