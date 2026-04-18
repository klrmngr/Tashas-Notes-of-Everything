---
type: pc
race: "Humanoid (dwarf)"
class:
 - "Duergar Soulblade"
subClass:
 - "CR 1"
cover: "Duergar Soulblade.png"
campaign:
locations:
tags:
  - race/dwarf
  - affinity/hostile
  - type/humanoid
  - size/medium
  - cr/1
  - source/mtf
---
###### Duergar Soulblade
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen's Tome of Foes
___

> [!infobox|no-t right]
> ![[Duergar Soulblade.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 1 (200 XP) |
> | :RiSwordFill: Type | Medium Humanoid (dwarf) |
> | :FasRulerVertical: Size | Medium |
> | :FasScaleBalanced: Alignment | Lawful Evil |
> | :FasShield: AC | 14 (leather armor) |
> | :FasHeart: HP | 18 (4d8) |
> | :FasUserGroup: Race | Humanoid (dwarf) |
> | :FasBook: Source | Mordenkainen's Tome of Foes |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 11 | 16 | 10 | 11 | 10 | 12 |
| **Mod** | +0 | +3 | +0 | +0 | +0 | +1 |

**Speed:** 25 ft. &nbsp;|&nbsp; **Senses:** darkvision 120 ft., passive Perception 10
**Languages:** Dwarvish, Undercommon
**Damage Resistances:** poison

---

### Traits

**Duergar Resilience.** The duergar has advantage on saving throws against poison, spells, and illusions, as well as to resist being charmed or paralyzed.

**Create Soulblade.** As a bonus action, the duergar can create a shortsword-sized, visible blade of psionic energy. The weapon appears in the duergar's hand and vanishes if it leaves the duergar's grip, or if the duergar dies or is incapacitated.

**Sunlight Sensitivity.** While in sunlight, the duergar has disadvantage on attack rolls, as well as on Wisdom (Perception) checks that rely on sight.


---

### Actions

**Soulblade.** Melee Weapon Attack: +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) force damage, or 10 (2d6 + 3) force damage while enlarged. If the soulblade has advantage on the attack roll, the attack deals an extra 3 (1d6) force damage.

**Enlarge (Recharges after a Short or Long Rest).** For 1 minute, the duergar magically increases in size, along with anything it is wearing or carrying. While enlarged, the duergar is Large, doubles its damage dice on Strength-based weapon attacks (included in the attacks), and makes Strength checks and Strength saving throws with advantage. If the duergar lacks the room to become Large, it attains the maximum size possible in the space available.

**Invisibility (Recharges after a Short or Long Rest).** The duergar magically turns invisible for up to 1 hour or until it attacks, it casts a spell, it uses its Enlarge, or its concentration is broken (as if concentrating on a spell). Any equipment the duergar wears or carries is invisible with it.


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