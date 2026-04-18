---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Duergar Stone Guard"
subClass:
 - "CR 2"
cover: "Duergar Stone Guard.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/2
  - source/mpmm
---
###### Duergar Stone Guard
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Duergar Stone Guard.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 2 (450 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Any alignment |
> | :FasShield: AC | 18 (chain mail, shield) |
> | :FasHeart: HP | 39 (6d8 + 12) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 18 | 11 | 14 | 11 | 10 | 9 |
| **Mod** | +4 | +0 | +2 | +0 | +0 | -1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Dwarvish, Undercommon
**Damage Resistances:** poison

---

### Traits

**Duergar Resilience.** The duergar has advantage on saving throws against spells and the charmed, paralyzed, and poisoned conditions.

**Phalanx Formation.** The duergar has advantage on attack rolls and Dexterity saving throws while standing within 5 feet of an ally wielding a shield.

**Sunlight Sensitivity.** While in sunlight, the duergar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Multiattack.** The duergar makes two Shortsword or Javelin attacks.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 11 (2d6 + 4) piercing damage while under the effect of Enlarge.

**Javelin.** Melee or Ranged Weapon Attack: +6 to hit, reach 5 ft. or range 30/120 ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 11 (2d6 + 4) piercing damage while under the effect of Enlarge.

**Invisibility (Recharges after a Short or Long Rest).** The duergar magically turns invisible for up to 1 hour or until it attacks, it forces a creature to make a saving throw, or its concentration is broken (as if concentrating on a spell). Any equipment the duergar wears or carries is invisible with it.


---

### Bonus Actions

**Enlarge (Recharges after a Short or Long Rest).** For 1 minute, the duergar magically increases in size, along with anything it is wearing or carrying. While enlarged, the duergar is Large, doubles its damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If the duergar lacks the room to become Large, it attains the maximum size possible in the space available.


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