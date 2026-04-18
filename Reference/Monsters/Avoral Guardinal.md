---
type: pc
race: "Celestial"
class:
 - "Avoral Guardinal"
subClass:
 - "CR 9"
cover: "Avoral Guardinal.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/9
  - source/mpp
---
###### Avoral Guardinal
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: MPP
___

> [!infobox|no-t right]
> ![[Avoral Guardinal.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 9 (5,000 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Good |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 172 (23d8 + 69) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | MPP |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 19 | 17 | 16 | 16 | 18 |
| **Mod** | +3 | +4 | +3 | +3 | +3 | +4 |

**Speed:** 30 ft., fly 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 21
**Languages:** Celestial, Common
**Saving Throws:** Dex +8, Cha +8
**Skills:** Perception +11, Religion +7
**Damage Resistances:** radiant
**Condition Immunities:** frightened

---

### Traits

**Dive Attack.** If the avoral is flying, dives at least 30 feet in a straight line toward a Medium or smaller creature, and ends within 5 feet of it, that creature must succeed on a DC 15 Strength saving throw or take 14 (4d6) piercing damage and have the prone condition.

**Flyby.** The avoral doesn't provoke an opportunity attack when it flies out of an enemy's reach.


---

### Actions

**Multiattack.** The avoral makes two Talon attacks. It can replace one attack with a use of Spellcasting.

**Talon.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 11 (2d6 + 4) piercing damage plus 13 (2d12) radiant damage.


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