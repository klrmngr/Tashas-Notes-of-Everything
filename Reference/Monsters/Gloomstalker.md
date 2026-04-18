---
type: pc
race: "Monstrosity"
class:
 - "Gloomstalker"
subClass:
 - "CR 6"
cover: "Gloomstalker.png"
campaign:
locations:
tags:
  - race/monstrosity
  - affinity/hostile
  - type/monstrosity
  - size/large
  - cr/6
  - source/egw
---
###### Gloomstalker
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Explorer's Guide to Wildemount
___

> [!infobox|no-t right]
> ![[Gloomstalker.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Large Monstrosity |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Neutral Evil |
> | :FasShield: AC | 15 (natural armor) |
> | :FasHeart: HP | 90 (12d10 + 24) |
> | :FasUserGroup: Race | Monstrosity |
> | :FasBook: Source | Explorer's Guide to Wildemount |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 22 | 16 | 14 | 5 | 17 | 14 |
| **Mod** | +6 | +3 | +2 | -3 | +3 | +2 |

**Speed:** 40 ft., fly 80 ft. &nbsp;|&nbsp; **Senses:** darkvision 240 ft, passive Perception 16
**Languages:** understands Common but can't speak
**Saving Throws:** Str +9, Dex +6
**Skills:** Athletics +9, Intimidation +5, Perception +6, Stealth +6
**Damage Vulnerabilities:** radiant

---

### Traits

**Shadowstep.** As a bonus action, the gloomstalker can teleport up to 40 feet to an unoccupied space it can see.

**Sunlight Sensitivity.** While in sunlight, the gloomstalker has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The gloomstalker makes two attacks: one with its bite and one with its claws.

**Bite.** Melee Weapon Attack: +9 to hit, reach 5 ft., one creature. *Hit:* 15 (2d8 + 6) piercing damage plus 7 (2d6) necrotic damage.

**Claws.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 13 (2d6 + 6) slashing damage plus 7 (2d6) necrotic damage.

**Snatch.** Melee Weapon Attack: +9 to hit, reach 5 ft., one Medium or smaller creature. *Hit:* 13 (2d6 + 6) slashing damage plus 7 (2d6) necrotic damage, and the target is grappled (escape DC 17). While grappled in this way, the target is restrained.

**Shriek (Recharge 6).** The gloomstalker emits a terrible shriek. Each enemy within 60 feet of the gloomstalker that can hear it must succeed on a DC 13 Constitution saving throw or be paralyzed until the end of the enemy's next turn.


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