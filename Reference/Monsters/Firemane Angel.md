---
type: pc
race: "Celestial"
class:
 - "Firemane Angel"
subClass:
 - "CR 12"
cover: "Firemane Angel.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/12
  - source/ggr
---
###### Firemane Angel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Firemane Angel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Good |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 135 (18d8 + 54) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 15 | 17 | 12 | 14 | 23 |
| **Mod** | +6 | +2 | +3 | +1 | +2 | +6 |

**Speed:** 40 ft., fly 120 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 16
**Languages:** all
**Saving Throws:** Str +10, Wis +6, Cha +10
**Skills:** Insight +6, Perception +6
**Damage Resistances:** fire; radiant; bludgeoning, piercing, slashing from nonmagical attacks
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Flyby.** The angel doesn't provoke an opportunity attack when it flies out of an enemy's reach.

**Magic Resistance.** The angel has advantage on saving throws against spells and other magical effects.

**Relentless (Recharges after a Short or Long Rest).** If the angel takes 21 damage or less that would reduce it to 0 hit points, it is reduced to 1 hit point instead.


---

### Actions

**Multiattack.** The angel makes two melee attacks.

**Longsword.** Melee Weapon Attack: +10 to hit, reach 5 ft., one target. *Hit:* 10 (1d8 + 6) slashing damage, or 11 (1d10 + 6) slashing damage if used with two hands, plus 22 (5d8) fire or radiant damage (angel's choice).


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