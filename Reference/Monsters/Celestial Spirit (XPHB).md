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
  - source/xphb
---
###### Celestial Spirit
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: XPHB
___

> [!infobox|no-t right]
> ![[Celestial Spirit.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | — (— XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral |
> | :FasShield: AC |  |
> | :FasHeart: HP | 40 + 10 for each spell level above 5 |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | XPHB |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 14 | 16 | 10 | 14 | 16 |
| **Mod** | +3 | +2 | +3 | +0 | +2 | +3 |

**Speed:** 30 ft., fly 40 ft. &nbsp;|&nbsp; **Senses:** Darkvision 60 ft., passive Perception 12
**Languages:** Celestial, understands the languages you know
**Damage Resistances:** radiant
**Condition Immunities:** charmed; frightened

---

### Actions

**Multiattack.** The spirit makes a number of attacks equal to half this spell's level (round down).

**Radiant Bow (Avenger Only).** r Bonus equals your spell attack modifier, range 600 ft. *Hit:* 2d6 + 2 + summonSpellLevel Radiant damage.

**Radiant Mace (Defender Only).** m Bonus equals your spell attack modifier, reach 5 ft. *Hit:* 1d10 + 3 + summonSpellLevel Radiant damage, and the spirit can choose itself or another creature it can see within 10 feet of the target. The chosen creature gains 1d10 Temporary Hit Points.

**Healing Touch (1/Day).** The spirit touches another creature. The target regains Hit Points equal to 2d8 + summonSpellLevel.


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