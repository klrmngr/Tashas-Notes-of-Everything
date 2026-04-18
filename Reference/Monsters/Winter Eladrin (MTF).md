---
type: pc
race: "Fey (elf)"
class:
 - "Winter Eladrin"
subClass:
 - "CR 10"
cover: "Winter Eladrin.png"
campaign:
locations:
tags:
  - race/elf
  - affinity/hostile
  - type/fey
  - size/medium
  - cr/10
  - source/mtf
---
###### Winter Eladrin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Winter Eladrin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 10 (5,900 XP) |
> | :RiSwordFill: Type | Medium Fey (elf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Chaotic Neutral |
> | :FasShield: AC | 19 (natural armor) |
> | :FasHeart: HP | 127 (17d8 + 51) |
> | :FasUserGroup: Race | Fey (elf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 10 | 16 | 18 | 17 | 13 |
| **Mod** | +0 | +0 | +3 | +4 | +3 | +1 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish, Sylvan
**Damage Resistances:** cold; bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Fey Step (Recharge 4–6).** As a bonus action, the eladrin can teleport up to 30 feet to an unoccupied space it can see.

**Magic Resistance.** The eladrin has advantage on saving throws against spells and other magical effects.

**Sorrowful Presence.** Any non-eladrin creature that starts its turn within 60 feet of the eladrin must make a DC 13 Wisdom saving throw. On a failed save, the creature is charmed for 1 minute. While charmed in this way, the creature has disadvantage on ability checks and saving throws. The charmed creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to any eladrin's Sorrowful Presence for the next 24 hours.
Whenever the eladrin deals damage to the charmed creature, it can repeat the saving throw, ending the effect on itself on a success.


---

### Actions

**Longsword.** Melee Weapon Attack: +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d8) slashing damage, or 5 (1d10) slashing damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. *Hit:* 4 (1d8) piercing damage.


---

### Reactions

**Frigid Rebuke.** When the eladrin takes damage from a creature the eladrin can see within 60 feet of it, the eladrin can force that creature to succeed on a DC 16 Constitution saving throw or take 11 (2d10) cold damage.


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