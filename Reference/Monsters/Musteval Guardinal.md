---
type: pc
race: "Celestial"
class:
 - "Musteval Guardinal"
subClass:
 - "CR 2"
cover: "Musteval Guardinal.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/small
  - cr/2
  - source/mpp
---
###### Musteval Guardinal
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Musteval Guardinal.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Small Celestial |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 13 |
> | :FasHeart: HP | 38 (11d6) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 12 | 16 | 11 | 14 | 15 | 14 |
| **Mod** | +1 | +3 | +0 | +2 | +2 | +2 |

**Speed:** 35 ft. &nbsp;|&nbsp; **Senses:** passive Perception 16
**Languages:** Celestial, Common
**Saving Throws:** Dex +5, Cha +4
**Skills:** Perception +6, Stealth +7
**Damage Resistances:** radiant
**Condition Immunities:** frightened

---

### Actions

**Multiattack.** The musteval makes two Bone Blade attacks.

**Bone Blade.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) slashing damage plus 3 (1d6) radiant damage.


---

### Reactions

**Skirmish Movement.** When a creature ends its turn within 5 feet of the musteval, the musteval can move up to half its speed. This movement doesn't provoke opportunity attacks.


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