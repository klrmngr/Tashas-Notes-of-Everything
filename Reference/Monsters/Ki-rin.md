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
  - size/large
  - cr/12
  - source/mpmm
---
###### Ki-rin
:FasPerson: Enemy &nbsp; | &nbsp; :FasBook: Mordenkainen Presents: Monsters of the Multiverse
___

> [!infobox|no-t right]
> ![[Ki-rin.png]]
> ###### Details:
> | Type | Stat |
> | ---- | ---- |
> | :FasCrown: CR | 12 (8,400 XP) |
> | :RiSwordFill: Type | Large Celestial |
> | :FasRulerVertical: Size | Large |
> | :FasScaleBalanced: Alignment | Lawful Good |
> | :FasShield: AC | 20 (natural armor) |
> | :FasHeart: HP | 153 (18d10 + 54) |
> | :FasUserGroup: Race | Celestial |
> | :FasBook: Source | Mordenkainen Presents: Monsters of the Multiverse |

---

### Stat Block

| | STR | DEX | CON | INT | WIS | CHA |
|---|---|---|---|---|---|---|
| **Score** | 21 | 16 | 16 | 19 | 20 | 20 |
| **Mod** | +5 | +3 | +3 | +4 | +5 | +5 |

**Speed:** 60 ft., fly 120 ft. ((hover)) &nbsp;|&nbsp; **Senses:** darkvision 120 ft., truesight 30 ft., passive Perception 19
**Languages:** all, telepathy 120 ft.
**Skills:** Perception +9, Insight +9, Religion +8
**Damage Immunities:** poison
**Condition Immunities:** poisoned

---

### Traits

**Legendary Resistance (3/Day).** If the ki-rin fails a saving throw, it can choose to succeed instead.

**Magic Resistance.** The ki-rin has advantage on saving throws against spells and other magical effects.


---

### Actions

**Multiattack.** The ki-rin makes two Hoof attacks and one Horn attack, or it makes two Sacred Fire attacks.

**Hoof.** Melee Weapon Attack: +9 to hit, reach 15 ft., one target. *Hit:* 10 (2d4 + 5) force damage.

**Horn.** Melee Weapon Attack: +9 to hit, reach 5 ft., one target. *Hit:* 14 (2d8 + 5) radiant damage.

**Sacred Fire.** Ranged Spell Attack: +9 to hit, range 120 ft., one target. *Hit:* 18 (3d8 + 5) radiant damage.


---

### Legendary Actions

### 

**Move.** The ki-rin moves up to half its speed without provoking opportunity attacks.

**Smite.** The ki-rin makes one Hoof, Horn, or Sacred Fire attack.


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