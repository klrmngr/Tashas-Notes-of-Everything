---
type: pc
race: "Celestial (angel)"
class:
 - "Deva"
subClass:
 - "CR 10"
cover: "Deva.png"
campaign:
locations:
tags:
  - race/angel
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/10
  - source/xmm
---
###### Deva
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XMM
___

> [!infobox|no-t right]
> ![[Deva.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Celestial (angel) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 17 |
> | :FasHeart: HP | 229 (27d8 + 108) |
> | :FasUserGroup: Race | Celestial (angel) |
> | :FasBook: Source | XMM |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 18 | 18 | 17 | 20 | 20 |
| **Mod** | +4 | +4 | +4 | +3 | +5 | +5 |

**Speed:** 30 ft., fly 90 ft. ((hover)) &nbsp;|&nbsp; **Senses:** Darkvision 120 ft., passive Perception 19
**Languages:** all; telepathy 120 ft.
**Saving Throws:** Wis +9, Cha +9
**Skills:** Insight +9, Perception +9
**Damage Resistances:** radiant
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Exalted Restoration.** If the deva dies outside Mount Celestia, its body disappears, and it gains a new body instantly, reviving with all its Hit Points somewhere in Mount Celestia.

**Magic Resistance.** The deva has Advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The deva makes two Holy Mace attacks.

**Holy Mace.** m +8, reach 5 ft. *Hit:* 7 (1d6 + 4) Bludgeoning damage plus 18 (4d8) Radiant damage.


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