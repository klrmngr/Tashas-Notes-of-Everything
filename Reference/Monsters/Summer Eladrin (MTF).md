---
type: pc
race: "Fey (elf)"
class:
 - "Summer Eladrin"
subClass:
 - "CR 10"
cover: "Summer Eladrin.png"
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
###### Summer Eladrin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Summer Eladrin.png]]
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
| **Score** | 19 | 21 | 16 | 14 | 12 | 18 |
| **Mod** | +4 | +5 | +3 | +2 | +1 | +4 |

**Speed:** 50 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 11
**Languages:** Common, Elvish, Sylvan
**Skills:** Athletics +8, Intimidation +8
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Fearsome Presence.** Any non-eladrin creature that starts its turn within 60 feet of the eladrin must make a DC 16 Wisdom saving throw. On a failed save, the creature becomes frightened for 1 minute. A creature can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success. If a creature's saving throw is successful or the effect ends for it, the creature is immune to any eladrin's Fearsome Presence for the next 24 hours.

**Fey Step (Recharge 4–6).** As a bonus action, the eladrin can teleport up to 30 feet to an unoccupied space it can see.

**Magic Resistance.** The eladrin has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The eladrin makes two weapon attacks.

**Longsword.** Melee Weapon Attack: +8 to hit, reach 5 ft., one target. *Hit:* 13 (2d8 + 4) slashing damage plus 4 (1d8) fire damage, or 15 (2d10 + 4) slashing damage plus 4 (1d8) fire damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +9 to hit, range 150/600 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage plus 4 (1d8) fire damage.


---

### Reactions

**Parry.** The eladrin adds 3 to its AC against one melee attack that would hit it. To do so, the eladrin must see the attacker and be wielding a melee weapon.


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