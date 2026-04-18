---
type: pc
race: "Fey (elf)"
class:
 - "Autumn Eladrin"
subClass:
 - "CR 10"
cover: "Autumn Eladrin.png"
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
###### Autumn Eladrin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Autumn Eladrin.png]]
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
| **Score** | 12 | 16 | 16 | 14 | 17 | 18 |
| **Mod** | +1 | +3 | +3 | +2 | +3 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 13
**Languages:** Common, Elvish, Sylvan
**Skills:** Insight +7, Medicine +7
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Enchanting Presence.** Any non-eladrin creature that starts its turn within 60 feet of the eladrin must make a DC 16 Wisdom saving throw. On a failed save, the creature is charmed by the eladrin for 1 minute. On a successful save, the creature becomes immune to any eladrin's Enchanting Presence for 24 hours.
Whenever the eladrin deals damage to the charmed creature, the creature can repeat the saving throw, ending the effect on itself on a success.

**Fey Step (Recharge 4–6).** As a bonus action, the eladrin can teleport up to 30 feet to an unoccupied space it can see.

**Magic Resistance.** The eladrin has advantage on saving throws against spells and other magical effects.


---

### Actions

**Longsword.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 5 (1d8 + 1) slashing damage plus 18 (4d8) psychic damage, or 6 (1d10 + 1) slashing damage plus 18 (4d8) psychic damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 18 (4d8) psychic damage.


---

### Reactions

**Foster Peace.** If a creature charmed by the eladrin hits with an attack roll while within 60 feet of the eladrin, the eladrin magically causes the attack to miss, provided the eladrin can see the attacker.


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