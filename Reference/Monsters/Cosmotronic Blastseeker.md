---
type: pc
race: "Humanoid (any race)"
class:
 - "Cosmotronic Blastseeker"
subClass:
 - "CR 4"
cover: "Cosmotronic Blastseeker.png"
campaign:
locations:
tags:
  - race/any race
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/4
  - source/ggr
---
###### Cosmotronic Blastseeker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Cosmotronic Blastseeker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 4 (1,100 XP) |
> | :RiSwordFill: Type | Medium Humanoid (any race) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 15 (chain shirt) |
> | :FasHeart: HP | 37 (5d8 + 15) |
> | :FasUserGroup: Race | Humanoid (any race) |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 15 | 16 | 18 | 9 | 12 |
| **Mod** | +2 | +2 | +3 | +4 | -1 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** passive Perception 11
**Languages:** any one language (usually Common)
**Saving Throws:** Dex +4, Con +5
**Skills:** Arcana +6, Intimidation +3, Perception +1

---

### Traits

**Empowered Spell (3/Day).** When the blastseeker rolls damage for a spell, it can reroll up to four dice of damage. It must use the new dice.

**Tides of Chaos (1/Day).** The blastseeker makes one attack roll, ability check, or saving throw with advantage.


---

### Actions

**Warhammer.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) bludgeoning damage, or 7 (1d10 + 2) bludgeoning damage if used with two hands.


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