---
type: pc
race: "Fey (elf)"
class:
 - "Spring Eladrin"
subClass:
 - "CR 10"
cover: "Spring Eladrin.png"
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
###### Spring Eladrin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Spring Eladrin.png]]
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
| **Score** | 14 | 16 | 16 | 18 | 11 | 18 |
| **Mod** | +2 | +3 | +3 | +4 | +0 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Elvish, Sylvan
**Skills:** Deception +8, Persuasion +8
**Damage Resistances:** bludgeoning, piercing, slashing from nonmagical attacks

---

### Traits

**Fey Step (Recharge 4–6).** As a bonus action, the eladrin can teleport up to 30 feet to an unoccupied space it can see.

**Joyful Presence.** Any non-eladrin creature that starts its turn within 60 feet of the eladrin must make a DC 16 Wisdom saving throw. On a failed save, the creature is charmed for 1 minute. On a successful save, the creature becomes immune to any eladrin's Joyful Presence for 24 hours.
Whenever the eladrin deals damage to the charmed creature, it can repeat the saving throw, ending the effect on itself on a success.

**Magic Resistance.** The eladrin has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The eladrin makes two weapon attacks. The eladrin can cast one spell in place of one of these attacks.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage plus 4 (1d8) psychic damage, or 7 (1d10 + 2) slashing damage plus 4 (1d8) psychic damage if used with two hands.

**Longbow.** Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 4 (1d8) psychic damage.


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