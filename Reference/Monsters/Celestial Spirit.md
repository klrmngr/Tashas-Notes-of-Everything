---
type: pc
race: "Celestial"
class:
 - "Celestial Spirit"
subClass:
 - "CR —"
cover: "Celestial Spirit.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/—
  - source/tce
---
###### Celestial Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Tasha's Cauldron of Everything
___

> [!infobox|no-t right]
> ![[Celestial Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Unaligned |
> | :FasShield: AC |  |
> | :FasHeart: HP | 40 + 10 for each spell level above 5th |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Tasha's Cauldron of Everything |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 10 | 14 | 16 |
| **Mod** | +3 | +2 | +3 | +0 | +2 | +3 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 12
**Languages:** Celestial, understands the languages you speak
**Damage Resistances:** radiant
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The celestial makes a number of attacks equal to half this spell's level (rounded down).

**Radiant Bow (Avenger Only).** Ranged Weapon Attack:  to hit, range 150/600 ft., one target. *Hit:* 2d6 + 2 + summonSpellLevel radiant damage.

**Radiant Mace (Defender Only).** Melee Weapon Attack:  to hit, reach 5 ft., one target. *Hit:* 1d10 + 3 + summonSpellLevel radiant damage, and the celestial can choose itself or another creature it can see within 10 feet of the target. The chosen creature gains 1d10 temporary hit points.

**Healing Touch (1/Day).** The celestial touches another creature. The target magically regains hit points equal to 2d8 + summonSpellLevel.


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