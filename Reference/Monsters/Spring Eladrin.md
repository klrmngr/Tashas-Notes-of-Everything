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
  - source/mpmm
---
###### Spring Eladrin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
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
> | :FasHeart: HP | 165 (22d8 + 66) |
> | :FasUserGroup: Race | Fey (elf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 14 | 16 | 16 | 18 | 11 | 18 |
| **Mod** | +2 | +3 | +3 | +4 | +0 | +4 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** darkvision 60 ft., passive Perception 10
**Languages:** Common, Elvish, Sylvan
**Skills:** Deception +8, Persuasion +8
**Damage Resistances:** psychic

---

### Traits

**Joyful Presence.** Any non-eladrin creature that starts its turn within 60 feet of the eladrin must make a DC 16 Wisdom saving throw. On a failed save, the creature becomes charmed by the eladrin for 1 minute. On a successful save, the creature becomes immune to any eladrin's Joyful Presence for 24 hours.
Whenever the eladrin deals damage to the charmed creature, the charmed creature can repeat the saving throw, ending the effect on itself on a success.

**Magic Resistance.** The eladrin has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The eladrin makes two Longsword or Longbow attacks. It can replace one attack with a use of Spellcasting.

**Longsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with two hands, plus 22 (5d8) psychic damage.

**Longbow.** Ranged Weapon Attack: +7 to hit, range 150/600 ft., one target. *Hit:* 7 (1d8 + 3) piercing damage plus 22 (5d8) psychic damage.


---

### Bonus Actions

**Fey Step (Recharge 4–6).** The eladrin teleports, along with any equipment it is wearing or carrying, up to 30 feet to an unoccupied space it can see.


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