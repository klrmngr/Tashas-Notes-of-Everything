---
type: pc
race: "Celestial"
class:
 - "Battleforce Angel"
subClass:
 - "CR 5"
cover: "Battleforce Angel.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/medium
  - cr/5
  - source/ggr
---
###### Battleforce Angel
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Battleforce Angel.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Medium Celestial |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 18 (plate armor) |
> | :FasHeart: HP | 66 (12d8 + 12) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 12 | 13 | 11 | 17 | 18 |
| **Mod** | +3 | +1 | +1 | +0 | +3 | +4 |

**Speed:** 30 ft., fly 90 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 120 ft., passive Perception 16
**Languages:** all
**Saving Throws:** Wis +6, Cha +7
**Skills:** Investigation +3, Perception +6
**Damage Resistances:** fire; radiant
**Condition Immunities:** charmed; exhaustion; frightened

---

### Traits

**Flyby.** The angel doesn't provoke an opportunity attack when it flies out of an enemy's reach.

**Magic Resistance.** The angel has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The angel makes two melee attacks. It also uses Battlefield Inspiration.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d8 + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands, plus 18 (4d8) radiant damage. If the target is within 5 feet of any of the angel's allies, the target takes an extra 2 (1d4) radiant damage.

**Battlefield Inspiration.** The angel chooses up to three creatures it can see within 30 feet of it. Until the end of the angel's next turn, each target can add a d4 to its attack rolls and saving throws.


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