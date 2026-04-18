---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Duergar Warlord"
subClass:
 - "CR 6"
cover: "Duergar Warlord.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/6
  - source/mtf
---
###### Duergar Warlord
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Duergar Warlord.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 6 (2,300 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 20 (plate armor, shield) |
> | :FasHeart: HP | 75 (10d8 + 30) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 17 | 12 | 12 | 14 |
| **Mod** | +4 | +0 | +3 | +1 | +1 | +2 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 11
**Languages:** Dwarvish, Undercommon
**Damage Resistances:** poison

---

### Traits

**Duergar Resilience.** The duergar has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed.

**Sunlight Sensitivity.** While in sunlight, the duergar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The duergar makes three hammer or javelin attacks and uses Call to Attack, or Enlarge if it is available.

**Psychic-Attuned Hammer.** Melee Weapon Attack: +7 to hit, reach 5 ft., one target. *Hit:* 9 (1d10 + 4) bludgeoning damage plus 5 (1d10) psychic damage, or 15 (2d10 + 4) bludgeoning damage plus 5 (1d10) psychic damage while enlarged,

**Javelin.** Melee or Ranged Weapon Attack: +7 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 11 (2d6 + 4) piercing damage while enlarged.

**Call to Attack.** Up to three allied duergar within 120 feet of this duergar that can hear it can each use their reaction to make one weapon attack.

**Enlarge (Recharges after a Short or Long Rest).** For 1 minute, the duergar magically increases in size, along with anything it is wearing or carrying. While enlarged, the duergar is Large, doubles its damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If the duergar lacks the room to become Large, it attains the maximum size possible in the space available.

**Invisibility (Recharge 4–6).** The duergar magically turns invisible for up to 1 hour or until it attacks, it casts a spell, it uses its Enlarge, or its concentration is broken (as if concentrating on a spell). Any equipment the duergar wears or carries is invisible with it.


---

### Reactions

**Scouring Instruction.** When an ally that the duergar can see makes a d20 roll, the duergar can roll a 1d6 and the ally can add the number rolled to the d20 roll by taking 3 (1d6) psychic damage. A creature immune to psychic damage can't be affected by Scouring Instruction.


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