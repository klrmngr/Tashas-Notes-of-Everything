---
type: pc
race: "Celestial"
class:
 - "Ki-rin"
subClass:
 - "CR 12"
cover: "Ki-rin.png"
campaign:
locations:
tags:
  - race/celestial
  - affinity/hostile
  - type/celestial
  - size/huge
  - cr/12
  - source/vgm
---
###### Ki-rin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Volo's Guide to Monsters
___

> [!infobox|no-t right]
> ![[Ki-rin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Huge Celestial |
> | :FasRulerVertical: Size | Huge |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 152 (16d12 + 48) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Volo's Guide to Monsters |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 16 | 16 | 19 | 20 | 20 |
| **Mod** | +5 | +3 | +3 | +4 | +5 | +5 |

**Speed:** 60 ft., fly 120 ft. ((hover)) &nbsp;|&nbsp; **Senses:** blindsight 30 ft., darkvision 120 ft., passive Perception 19
**Languages:** all, telepathy 120 ft.
**Skills:** Insight +9, Perception +9, Religion +8
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the ki-rin fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The ki-rin has advantage on saving throws against spells and other magical effects.

**Magic Weapons.** The ki-rin's weapon attacks are magical.


---

### Actions

**Multiattack.** The ki-rin makes three attacks: two with its hooves and one with its horn.

**Hoof.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 10 (2d4 + 5) bludgeoning damage.

**Horn.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) piercing damage.


---

### Legendary Actions

### 

**Detect.** The ki-rin makes a Wisdom (Perception) check or a Wisdom (Insight) check.

**Smite.** The ki-rin makes a hoof attack or casts sacred flame.

**Move.** The ki-rin moves up to its half its speed without provoking opportunity attacks.


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