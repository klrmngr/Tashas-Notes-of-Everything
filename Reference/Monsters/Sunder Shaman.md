---
type: pc
race: "Giant"
class:
 - "Sunder Shaman"
subClass:
 - "CR 10"
cover: "Sunder Shaman.png"
campaign:
locations:
tags:
  - race/giant
  - affinity/hostile
  - type/giant
  - size/huge
  - cr/10
  - source/ggr
---
###### Sunder Shaman
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Sunder Shaman.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Huge Giant |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 20 (stone armor) |
> | :FasHeart: HP | 138 (12d12 + 60) |
> | :FasUserGroup: Race | Giant |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 23 | 15 | 21 | 10 | 12 | 9 |
| **Mod** | +6 | +2 | +5 | +0 | +1 | -1 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 15
**Languages:** Giant
**Saving Throws:** Dex +6, Con +9, Wis +5
**Skills:** Athletics +10, Perception +5

---

### Traits

**Reckless.** At the start of its turn, the giant can gain advantage on all melee weapon attack rolls it makes during that turn, but attack rolls against it have advantage until the start of its next turn.

**Siege Monster.** The giant deals double damage to objects and structures.

**Stone Camouflage.** The giant has advantage on Dexterity (Stealth) checks made to hide in rocky terrain.


---

### Actions

**Multiattack.** The giant makes two slam attacks. The first of those attacks that hits deals an extra 18 (4d8) damage if the giant has taken damage since its last turn.

**Slam.** Melee Weapon Attack: +10 to hit, reach 15 ft., one target. *Hit:* 24 (4d8 + 6) bludgeoning damage.

**Rock.** Ranged Weapon Attack: +10 to hit, range 60/240 ft., one target. *Hit:* 28 (4d10 + 6) bludgeoning damage. If the target is a creature, it must succeed on a DC 18 Strength saving throw or be knocked prone.


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