---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Grandolpha Muzgardt"
subClass:
 - "CR 2"
cover: "Grandolpha Muzgardt.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/idrotf
---
###### Grandolpha Muzgardt
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Icewind Dale: Rime of the Frostmaiden
___

> [!infobox|no-t right]
> ![[Grandolpha Muzgardt.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 9 |
> | :FasHeart: HP | 59 (7d8 + 28) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Icewind Dale: Rime of the Frostmaiden |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 9 | 18 | 13 | 17 | 16 |
| **Mod** | +2 | -1 | +4 | +1 | +3 | +3 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 13
**Languages:** Common, Dwarvish, Undercommon
**Damage Resistances:** poison

---

### Traits

**Duergar Resilience.** Grandolpha has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed.

**Sunlight Sensitivity.** While in sunlight, Grandolpha has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Poison Spray (Cantrip).** Grandolpha extends her hand toward a creature she can see within 10 feet of her and projects a puff of noxious gas from her palm. The creature must succeed on a DC 13 Constitution saving throw or take 13 (2d12) poison damage.


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