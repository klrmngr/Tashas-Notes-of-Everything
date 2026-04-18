---
type: pc
race: "Celestial"
class:
 - "Felidar"
subClass:
 - "CR 5"
cover: "Felidar.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/large
  - cr/5
  - source/ggr
---
###### Felidar
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Guildmasters' Guide to Ravnica
___

> [!infobox|no-t right]
> ![[Felidar.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 5 (1,800 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Neutral |
> | :FasShield: AC | 17 (natural armor) |
> | :FasHeart: HP | 93 (11d10 + 33) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Guildmasters' Guide to Ravnica |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 19 | 16 | 17 | 10 | 17 | 14 |
| **Mod** | +4 | +3 | +3 | +0 | +3 | +2 |

**Speed:** 40 ft. &nbsp;|&nbsp; **Senses:** truesight 120 ft., passive Perception 16
**Languages:** understands Celestial and Common but can't speak
**Saving Throws:** Dex +6, Wis +6, Cha +5
**Skills:** Insight +6, Perception +6

---

### Traits

**Bonding.** The felidar can magically bond with one creature it can see, right after spending at least 1 hour observing that creature while within 30 feet of it. The bond lasts until the felidar bonds with a different creature or until the bonded creature dies. This bond has the following effects: The felidar and the bonded creature can communicate telepathically with each other at a distance of up to 100 feet. The felidar can sense the direction and distance to the bonded creature if they're on the same plane of existence. As an action, the felidar or the bonded creature can sense what the other sees and hears, during which time it loses its own sight and hearing. This effect lasts until the start of its next turn.

**Keen Hearing and Sight.** The felidar has advantage on Wisdom (Perception) checks that rely on hearing or sight.

**Pounce.** If the felidar moves at least 20 feet straight toward a creature and hits it with a claw attack on the same turn, that target must succeed on a DC 15 Strength saving throw or be knocked prone. If the target is prone, the felidar can make one claw attack against it as a bonus action.


---

### Actions

**Multiattack.** The felidar makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 17 (3d8 + 4) piercing damage.

**Claws.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 14 (3d6 + 4) slashing damage.


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