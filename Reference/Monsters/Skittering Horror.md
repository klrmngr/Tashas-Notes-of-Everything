---
type: pc
race: "Aberration"
class:
 - "Skittering Horror"
subClass:
 - "CR 15"
cover: "Skittering Horror.png"
campaign:
locations:
tags:
  - race/aberration
  - affinity/hostile
  - type/aberration
  - size/huge
  - cr/15
  - source/ggr
---
###### Skittering Horror
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Skittering Horror.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 15 (13,000 XP) |
> | :RiSwordFill: Type | Huge Aberration |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 228 (24d12 + 72) |
> | :FasUserGroup: Race | Aberration |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 16 | 17 | 2 | 14 | 18 |
| **Mod** | +6 | +3 | +3 | -4 | +2 | +4 |

**Speed:** 40 ft., climb 40 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 17
**Languages:** —
**Skills:** Perception +7, Stealth +8
**Damage Vulnerabilities:** radiant
**Condition Immunities:** frightened

---

### Traits

**Spider Climb.** The horror can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.

**Sunlight Sensitivity.** While in sunlight, the horror has disadvantage on attack rolls and on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The horror can use its Maddening Presence and make three attacks: one with its bite and two with its claws.

**Bite.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 28 (4d10 + 6) piercing damage.

**Claws.** Melee Weapon Attack: +11 to hit, reach 10 ft., one target. *Hit:* 24 (4d8 + 6) slashing damage.

**Maddening Presence.** The horror targets one creature it can see within 30 feet of it. If the target can see or hear the horror, the target must make a DC 17 Wisdom saving throw. On a failed saving throw, the target becomes paralyzed until the end of its next turn. If a creature's saving throw is successful, the creature is immune to the horror's Maddening Presence for the next 24 hours.


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