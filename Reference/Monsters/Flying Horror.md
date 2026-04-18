---
type: pc
race: "Aberration"
class:
 - "Flying Horror"
subClass:
 - "CR 3"
cover: "Flying Horror.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/medium
  - cr/3
  - source/ggr
---
###### Flying Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Flying Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 3 (700 XP) |
> | :RiSwordFill: Type | Medium Aberration |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 16 (natural armor) |
> | :FasHeart: HP | 49 (9d8 + 9) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 9 | 20 | 12 | 2 | 15 | 16 |
| **Mod** | -1 | +5 | +1 | -4 | +2 | +3 |

**Speed:** 30 ft., fly 60 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 14
**Languages:** —
**Skills:** Perception +4, Stealth +7
**Damage Vulnerabilities:** radiant
**Condition Immunities:** frightened

---

### Traits

**Fear Frenzy.** The horror has advantage on attack rolls against frightened creatures.

**Sunlight Sensitivity.** While in sunlight, the horror has disadvantage on attack rolls and on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d6 + 5) slashing damage plus 14 (4d6) psychic damage.

**Frightening Screech (Recharge 5–6).** The horror screeches. Each creature within 30 feet of it that can hear it must succeed on a DC 13 Wisdom saving throw or be frightened of it for 1 minute. The frightened creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to the horror's Frightening Screech for the next 24 hours.


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