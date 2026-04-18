---
type: pc
race: "Humanoid (gnome)"
class:
 - "Tixie Tockworth"
subClass:
 - "CR 7"
cover: "Tixie Tockworth.png"
campaign:
locations:
tags:
  - race/gnome
  - affinity/hostile
  - type/humanoid
  - size/small
  - cr/7
  - source/kftgv
---
###### Tixie Tockworth
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Keys from the Golden Vault
___

> [!infobox|no-t right]
> ![[Tixie Tockworth.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 7 (2,900 XP) |
> | :RiSwordFill: Type | Small Humanoid (gnome) |
> | :FasRulerVertical: Size | Small |
> | :FasScaleBalanced: Alignment | Chaotic Evil |
> | :FasShield: AC | 17 (natural armor, shield) |
> | :FasHeart: HP | 75 (10d6 + 40) |
> | :FasUserGroup: Race | Humanoid (gnome) |
> | :FasBook: Source | Keys from the Golden Vault |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 16 | 13 | 18 | 17 | 9 | 10 |
| **Mod** | +3 | +1 | +4 | +3 | -1 | +0 |

**Speed:** 30 ft. &nbsp;|&nbsp; **Senses:** truesight 60 ft., passive Perception 12
**Languages:** Common, Gnomish, Terran, Undercommon
**Saving Throws:** Int +6, Wis +2
**Skills:** Arcana +9, Perception +2

---

### Traits

**Force Field.** Tockworth generates a magical force field around herself. This force field has 15 hit points and regains all its hit points at the start of each of Tockworth's turns, but it ceases to function if Tockworth drops to 0 hit points. Any damage Tockworth takes is subtracted from the force field's hit points first. Each time the force field regains hit points, the following conditions end on Tockworth: grappled, restrained, and stunned.


---

### Actions

**Multiattack.** Tockworth makes three Shortsword or Lightning Discharge attacks.

**Shortsword.** Melee Weapon Attack: +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6 + 3) piercing damage plus 10 (3d6) force damage.

**Lightning Discharge.** Ranged Spell Attack: +6 to hit, range 60 ft., one creature. *Hit:* 16 (3d10) lightning damage.


---

### Bonus Actions

**Scalding Steam (Recharge 5–6).** Tockworth emits a jet of piping-hot steam in a 15-foot cone. Each creature in that cone must make a DC 15 Dexterity saving throw, taking 10 (3d6) fire damage on a failed save, or half as much damage on a successful one.


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